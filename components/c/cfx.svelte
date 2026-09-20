<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGRKc3LcVw)" class="cs9t_f_pi"/><defs><linearGradient id="SVGRKc3LcVw" x1="19.579" x2="3.056" y1="17.58" y2="8.814" gradientUnits="userSpaceOnUse"><stop class="eitqnwsbl"/><stop offset="1" class="grv74owko"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:cfx" {...props}></Icon>
<style>
:global(.cs9t_f_pi) {
  d: path("m12.01 3l7.569 7.257l-.014 3.472l-7.589-7.276l-7.531 7.224l-.024-3.401zm0 14.637l3.931-3.766l1.743 1.672L11.991 21l-5.675-5.438l5.693-5.457l1.744 1.672l-3.927 3.766l2.188 2.094z");
}

:global(.eitqnwsbl) {
  stop-color: var(--svg-color--13c77f, #13c77f);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.grv74owko) {
  stop-color: var(--svg-color--295db2, #295db2);
}

</style>
