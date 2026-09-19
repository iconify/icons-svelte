<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivhbr1sli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivhbr1sli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:border-all-01" {...props}></Icon>
