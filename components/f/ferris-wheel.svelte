<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ovj65uyrr.css';
import '../../css/z/z-i-v5b9z.css';
import '../../css/c/ck3l_yb1f.css';
import '../../css/d/dz0vutsnd.css';
import '../../css/h/hs_ytft2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ovj65uyrr"/><path class="z-i-v5b9z"/><path class="ck3l_yb1f"/><path class="dz0vutsnd"/><path class="hs_ytft2u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:ferris-wheel" {...props}></Icon>
