<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":220};
const content = `<path class="nlsomdb2f"/><path class="eosy8mbho"/><path class="c0qffzbvf"/><path class="lrugpbqym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:mockflow-icon" {...props}></Icon>
<style>
:global(.c0qffzbvf) {
  fill: var(--svg-color--7957ff, #7957ff);
  d: path("M219.429 48.762h-73.143V0H256z");
}

:global(.eosy8mbho) {
  fill: var(--svg-color--1b7ce2, #1b7ce2);
  d: path("M90.006 84.114L51.81 141.206l-3.048 4.877h-.203L0 219.429V0z");
}

:global(.lrugpbqym) {
  fill: var(--svg-color--f845c6, #f845c6);
  d: path("M146.286 0v219.429l-97.524-73.346l3.048-4.877l38.196-57.092z");
}

:global(.nlsomdb2f) {
  fill: var(--svg-color--7957ff, #7957ff);
  d: path("m146.286 152.381l73.143-51.403h-73.143z");
}

</style>
