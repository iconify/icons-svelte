<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkoq81btf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="xkoq81btf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-fire-extinguisher" {...props}></Icon>
