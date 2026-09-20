<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="zut58gbmm"/><path class="icel-5blf"/><path class="jyudtqbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-luxembourg" {...props}></Icon>
<style>
:global(.icel-5blf) {
  fill: var(--svg-color--ed2939, #ed2939);
  d: path("M32 5H4a4 4 0 0 0-4 4v5h36V9a4 4 0 0 0-4-4");
}

:global(.jyudtqbhp) {
  fill: var(--svg-color--00a1de, #00a1de);
  d: path("M4 31h28a4 4 0 0 0 4-4v-5H0v5a4 4 0 0 0 4 4");
}

:global(.zut58gbmm) {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 14h36v8H0z");
}

</style>
