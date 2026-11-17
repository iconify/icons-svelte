<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb-y9pbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ladder-fill" {...props}></Icon>
<style>
:global(.kb-y9pbvh) {
  fill: currentColor;
  d: path("M9 3v3h6V3a1 1 0 0 1 2 0v18a1 1 0 0 1-2 0v-3H9v3a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m0 8h6V8H9Zm0 2v3h6v-3Z");
}

</style>
