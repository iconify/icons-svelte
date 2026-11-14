<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vcyc4b3ql"/><path class="nb_q0pbya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dependency-locked" {...props}></Icon>
<style>
:global(.nb_q0pbya) {
  d: path("m5.25 13.5l2 2l2-2m5.75 4h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vcyc4b3ql) {
  d: path("M2.5 3H12v5.5H2.5Zm0 12.5H12V21H2.5Zm4.75-7v7");
}

</style>
