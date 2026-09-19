<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_o7nh8_y.css';
import '../../css/h/ht-fiobcn.css';
import '../../css/e/ebo3gi1sn.css';
import '../../css/o/ohefunpbk.css';
import '../../css/u/uj-21biux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="i_o7nh8_y"/><circle class="ht-fiobcn"/><path class="ebo3gi1sn"/><path class="ohefunpbk"/><path class="uj-21biux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-saas-console" {...props}></Icon>
