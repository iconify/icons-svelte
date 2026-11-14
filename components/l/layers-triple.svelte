<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qeh_2obwx"/><path class="clxk-sb_d"/><path class="lxczy9weo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:layers-triple" {...props}></Icon>
<style>
:global(.clxk-sb_d) {
  d: path("m2.5 12l9.5 5.5l9.5-5.5");
}

:global(.lxczy9weo) {
  d: path("m2.5 16l9.5 5.5l9.5-5.5");
}

:global(.qeh_2obwx) {
  d: path("M12 2.5L21.5 8L12 13.5L2.5 8Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
