<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="komtombne"/><path class="g_9re3uap"/><path class="jsq7yzb3y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:lith" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g_9re3uap) {
  fill: var(--svg-color--e96036, #e96036);
  d: path("M17.464 10.072a3.536 3.536 0 1 0 0-7.072a3.536 3.536 0 0 0 0 7.072");
}

:global(.jsq7yzb3y) {
  fill: var(--svg-color--000, #000);
  d: path("M6.536 21a3.536 3.536 0 1 0 0-7.071a3.536 3.536 0 0 0 0 7.071m10.928 0a3.536 3.536 0 1 0 0-7.071a3.536 3.536 0 0 0 0 7.071");
}

:global(.komtombne) {
  fill: var(--svg-color--000, #000);
  d: path("M6.536 10.072a3.536 3.536 0 1 0 0-7.072a3.536 3.536 0 0 0 0 7.072");
}

</style>
