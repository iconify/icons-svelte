<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxiw_rb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vxiw_rb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:git-alt" {...props}></Icon>
