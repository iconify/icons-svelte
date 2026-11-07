<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lz14ttf8r.css';
import '../../css/m/my5268blj.css';
import '../../css/x/xjmp9lmjf.css';
import '../../css/z/zs-ga2d7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lz14ttf8r"/><path class="my5268blj"/><circle class="xjmp9lmjf"/><path class="zs-ga2d7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-clock-linear" {...props}></Icon>
