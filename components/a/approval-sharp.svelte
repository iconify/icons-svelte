<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k67u2cc6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:approval-sharp" {...props}></Icon>
<style>
:global(.k67u2cc6u) {
  fill: currentColor;
  d: path("M4 22v-8h16v8zm2-4h12v-2H6zm6-4L7 7q0-2.075 1.463-3.537T12 2t3.538 1.463T17 7z");
}

</style>
