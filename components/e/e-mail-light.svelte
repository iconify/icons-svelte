<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/d/da4x8hbcl.css';
import '../../css/a/aqhok2bbj.css';
import '../../css/m/mzgzwghgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="da4x8hbcl"/><circle class="aqhok2bbj"/><path class="mzgzwghgb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:e-mail-light" {...props}></Icon>
