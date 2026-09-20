<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="z4bku6yml"/><path class="s20hrmm1w"/><path class="bsrs8cbgd"/><path class="u5cs-y6gz"/><path class="ib6caf3vb"/><path class="qqz53fars"/><path class="soa-tzv3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-puerto-rico" {...props}></Icon>
<style>
:global(.bsrs8cbgd) {
  fill: var(--svg-color--ea0b19, #ea0b19);
  d: path("m18 18l-4.154 3H36v-6H13.846z");
}

:global(.ib6caf3vb) {
  fill: var(--svg-color--ea0b19, #ea0b19);
  d: path("M1.371 30.01c.703.615 1.621.99 2.629.99h28a4 4 0 0 0 4-4v-1H6.923z");
}

:global(.qqz53fars) {
  fill: var(--svg-color--0f55ec, #0f55ec);
  d: path("M13.846 21L18 18l-4.154-3l-6.923-5l-5.552-4.01A4 4 0 0 0 0 9v18c0 1.201.532 2.276 1.371 3.01L6.923 26z");
}

:global(.s20hrmm1w) {
  fill: var(--svg-color--eee, #eee);
  d: path("M13.846 15H36v-5H6.923z");
}

:global(.soa-tzv3a) {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.187 18.838l2.313-1.675H7.641l-.888-2.726l-.89 2.726H3l2.315 1.677l-.89 2.723l2.325-1.684l2.325 1.684z");
}

:global(.u5cs-y6gz) {
  fill: var(--svg-color--eee, #eee);
  d: path("M6.923 26H36v-5H13.846z");
}

:global(.z4bku6yml) {
  fill: var(--svg-color--ea0b19, #ea0b19);
  d: path("M32 5H4a3.98 3.98 0 0 0-2.629.99L6.923 10H36V9a4 4 0 0 0-4-4");
}

</style>
