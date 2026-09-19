<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbma66bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbma66bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pentagon-01" {...props}></Icon>
