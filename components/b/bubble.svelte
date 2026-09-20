<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/q/qgctxwzlr.css';
import '../../css/o/ows_o8gdi.css';
import '../../css/q/qliqwmf6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="qgctxwzlr"/><circle class="ows_o8gdi"/><circle class="qliqwmf6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:bubble" {...props}></Icon>
