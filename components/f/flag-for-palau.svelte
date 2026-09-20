<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="zil08eqzc"/><circle class="al6gztbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-palau" {...props}></Icon>
<style>
:global(.al6gztbew) {
  fill: var(--svg-color--ffde00, #FFDE00);
  cx: 14.8px;
  cy: 18px;
  r: 8px;
}

:global(.zil08eqzc) {
  fill: var(--svg-color--4aadd6, #4AADD6);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4z");
}

</style>
