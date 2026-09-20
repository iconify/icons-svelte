<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wde4g70nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wde4g70nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:box" {...props}></Icon>
