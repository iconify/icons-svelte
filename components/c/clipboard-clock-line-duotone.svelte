<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vsdjuskpk.css';
import '../../css/m/my5268blj.css';
import '../../css/x/xjmp9lmjf.css';
import '../../css/j/jn1z35blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vsdjuskpk"/><path class="my5268blj"/><circle class="xjmp9lmjf"/><path class="jn1z35blr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-clock-line-duotone" {...props}></Icon>
