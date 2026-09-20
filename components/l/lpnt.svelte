<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xznn5_baa"/><path clip-rule="evenodd" class="vbquwab2j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:lpnt" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.vbquwab2j) {
  fill: var(--svg-color--e82f59, #e82f59);
  fill-rule: evenodd;
  d: path("M8.7 6.6H3V21h14.4v-5.7zm7.5 13.2v-2.4H6.6V7.8H4.2v12z");
}

:global(.xznn5_baa) {
  fill: var(--svg-color--141b30, #141b30);
  d: path("M5.4 3H21v15.6l-3.6-3.3V6.6H8.7z");
}

</style>
