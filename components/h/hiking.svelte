<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9bf-gbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9bf-gbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hiking" {...props}></Icon>
