<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":266};
const content = `<path class="mucs4acic"/><path class="xjdihdc4i"/><path class="ap58jmchm"/><path class="jz-x2pbah"/><path class="wlnzmobhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:nats-icon" {...props}></Icon>
<style>
:global(.ap58jmchm) {
  fill: var(--svg-color--8dc63f, #8dc63f);
  d: path("M256 103.863v103.769h-84.193v57.395l-62.622-57.205l18.815-.76V103.863z");
}

:global(.jz-x2pbah) {
  fill: var(--svg-color--375c93, #375c93);
  d: path("M128 103.863v120.678l-18.815-16.719H0V103.863z");
}

:global(.mucs4acic) {
  fill: var(--svg-color--34a574, #34a574);
  d: path("M128 0h128v103.768H128z");
}

:global(.wlnzmobhi) {
  fill: var(--svg-color--fff, #fff);
  d: path("M181.024 134.177V48.273h30.599v111.086H165.25l-93.6-87.424v87.519H40.956V48.273h47.988z");
}

:global(.xjdihdc4i) {
  fill: var(--svg-color--27aae1, #27aae1);
  d: path("M0 0h128v103.768H0z");
}

</style>
