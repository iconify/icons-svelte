<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4sxp5bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="t4sxp5bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:comments" {...props}></Icon>
