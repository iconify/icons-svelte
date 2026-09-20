<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="q7bn-mlfe"/><path class="ko78l5bky"/><path class="fkagtxbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-estonia" {...props}></Icon>
<style>
:global(.fkagtxbpe) {
  fill: var(--svg-color--eee, #eee);
  d: path("M32 31H4a4 4 0 0 1-4-4v-4h36v4a4 4 0 0 1-4 4");
}

:global(.ko78l5bky) {
  fill: var(--svg-color--4891d9, #4891d9);
  d: path("M32 5H4a4 4 0 0 0-4 4v5h36V9a4 4 0 0 0-4-4");
}

:global(.q7bn-mlfe) {
  fill: var(--svg-color--141414, #141414);
  d: path("M0 14h36v9H0z");
}

</style>
