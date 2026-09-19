<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5vgbcb_s.css';
import '../../css/e/e92j8hbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="y5vgbcb_s"/><path class="e92j8hbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:gl-4x3" {...props}></Icon>
