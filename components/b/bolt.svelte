<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp3oi9bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:bolt" {...props}></Icon>
<style>
:global(.cp3oi9bpb) {
  fill: currentColor;
  d: path("m8 22l1-7H4l9-13h2l-1 8h6L10 22z");
}

</style>
