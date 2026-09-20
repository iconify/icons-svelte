<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<defs><radialGradient id="SVGnL1xucik" cx="50%" cy="50%" r="49.789%" fx="50%" fy="50%"><stop offset="0%" class="osy8scnfb"/><stop offset="49.285%" class="osy8scnfb"/><stop offset="100%" class="tiy-3rb_y"/></radialGradient><radialGradient id="SVGzG1r7dEc" cx="50%" cy="50%" r="49.603%" fx="50%" fy="50%"><stop offset="0%" class="oiszezb7i"/><stop offset="18.73%" class="i174ypf_z"/><stop offset="100%" class="u3mgx8kdc"/></radialGradient><circle id="SVGN5eQqeMK" class="ugn0xccey"/></defs><circle class="vi6iaxsyk"/><mask id="SVGMX2wGdvm" class="n1mjunbsu"><use href="#SVGN5eQqeMK"/></mask><circle fill="url(#SVGnL1xucik)" mask="url(#SVGMX2wGdvm)" class="achp2yxpl"/><circle fill="url(#SVGzG1r7dEc)" mask="url(#SVGMX2wGdvm)" class="w44pw6byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:moon" {...props}></Icon>
<style>
:global(.achp2yxpl) {
  cx: 199.694px;
  cy: 105.369px;
  r: 128px;
}

:global(.i174ypf_z) {
  stop-color: var(--svg-color--320194, #320194);
}

:global(.n1mjunbsu) {
  fill: var(--svg-color--fff, #fff);
}

:global(.oiszezb7i) {
  stop-color: var(--svg-color--35019e, #35019e);
}

:global(.osy8scnfb) {
  stop-color: var(--svg-color--4600d1, #4600d1);
}

:global(.tiy-3rb_y) {
  stop-color: var(--svg-color--35009f, #35009f);
}

:global(.u3mgx8kdc) {
  stop-color: var(--svg-color--206, #206);
}

:global(.ugn0xccey) {
  cx: 128px;
  cy: 128px;
  r: 128px;
}

:global(.vi6iaxsyk) {
  cx: 128px;
  cy: 128px;
  r: 128px;
  fill: var(--svg-color--5805ff, #5805ff);
}

:global(.w44pw6byy) {
  cx: 275.372px;
  cy: 82.376px;
  r: 128px;
}

</style>
