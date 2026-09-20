<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bva9_bcop.css';
import '../../css/m/mkzt5foon.css';
import '../../css/h/h5vc_wttc.css';
import '../../css/n/n7mdeobel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bva9_bcop"/><path class="mkzt5foon"/><path class="h5vc_wttc"/><path class="n7mdeobel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:flip-h" {...props}></Icon>
