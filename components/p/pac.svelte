<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGDpmlNc9T)" class="t5nyi-mdr"/><defs><linearGradient id="SVGDpmlNc9T" x1="5.368" x2="22.56" y1="3" y2="15.668" gradientUnits="userSpaceOnUse"><stop class="zqc_bfb8q"/><stop offset="1" class="d6ntvh61n"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:pac" {...props}></Icon>
<style>
:global(.d6ntvh61n) {
  stop-color: var(--svg-color--0290a4, #0290a4);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.t5nyi-mdr) {
  d: path("M18.631 12L12 3l-6.632 9l5.685 7.674v-7.712l-.858 3.629l-2.724-3.586l4.534-6.097L16.533 12l-2.728 3.586L12 8.376V21z");
}

:global(.zqc_bfb8q) {
  stop-color: var(--svg-color--00ddf8, #00ddf8);
}

</style>
