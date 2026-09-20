<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="p4oh0gb8h"/><path class="alw03nfmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-flag-switzerland" {...props}></Icon>
<style>
:global(.alw03nfmq) {
  fill: var(--svg-color--fff, #fff);
  d: path("M25 16.063h-5v-5h-4v5h-5V20h5v5.063h4V20h5z");
}

:global(.p4oh0gb8h) {
  fill: var(--svg-color--d32d27, #d32d27);
  d: path("M31 27a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h18a4 4 0 0 1 4 4z");
}

</style>
