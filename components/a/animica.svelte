<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x02vfhbzu"><path clip-rule="evenodd" class="kq2-3vbvq"/><path class="fzaarub1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:animica" {...props}></Icon>
<style>
:global(.fzaarub1g) {
  d: path("m12 7.138l3.455 10.045h-6.91z");
}

:global(.kq2-3vbvq) {
  fill-rule: evenodd;
  d: path("M12 3a9 9 0 1 0 0 18a9 9 0 0 0 0-18m0 1.768a7.232 7.232 0 1 1 0 14.464a7.232 7.232 0 0 1 0-14.464");
}

:global(.x02vfhbzu) {
  fill: var(--svg-color--2e63ff, #2e63ff);
}

</style>
