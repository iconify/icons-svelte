<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><circle class="doa4-pbgn"/><path class="az3ocgbvy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:evergreen-icon" {...props}></Icon>
<style>
:global(.az3ocgbvy) {
  fill: var(--svg-color--fff, #fff);
  d: path("M135.97 176.049v31.88h-15.94v-31.88zM128 56.5l55.79 111.579H72.21z");
}

:global(.doa4-pbgn) {
  cx: 128px;
  cy: 128px;
  r: 128px;
  fill: var(--svg-color--38a065, #38a065);
}

:global(.ft5dv1b6b) {
  fill: none;
}

</style>
