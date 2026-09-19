<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq4o_fgkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="yq4o_fgkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrows-left-right-to-line" {...props}></Icon>
