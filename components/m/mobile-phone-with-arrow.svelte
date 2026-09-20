<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="a-epqboys"/><path class="d8t5uubml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:mobile-phone-with-arrow" {...props}></Icon>
<style>
:global(.a-epqboys) {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M18 36s-4 0-4-4V4s0-4 4-4h14s4 0 4 4v28s0 4-4 4z");
}

:global(.d8t5uubml) {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M16 5h18v26H16zm-3 11s1 1 1 2s-1 2-1 2l-5 5c-1 1-3 1-3-1v-3H2s-2 0-2-2v-2c0-2 2-2 2-2h3v-3c0-2 2-2 3-1z");
}

</style>
