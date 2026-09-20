<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="he5jmsbko"/><path class="pd-hacc_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-flag-indonesia" {...props}></Icon>
<style>
:global(.he5jmsbko) {
  fill: var(--svg-color--dc1f26, #dc1f26);
  d: path("M32 5H4a4 4 0 0 0-4 4v9h36V9a4 4 0 0 0-4-4");
}

:global(.pd-hacc_i) {
  fill: var(--svg-color--eee, #eee);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4v-9h36z");
}

</style>
