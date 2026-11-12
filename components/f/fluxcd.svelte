<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hizqcsbyt.css';
import '../../css/x/xsfw_6dos.css';
import '../../css/y/yvtc_v5-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hizqcsbyt"/><path class="xsfw_6dos"/><path class="yvtc_v5-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:fluxcd" {...props}></Icon>
