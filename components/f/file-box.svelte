<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c094mc13p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c094mc13p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:file-box" {...props}></Icon>
