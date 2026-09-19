<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmbk2pjqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-vertical-distribute" {...props}></Icon>
<style>
:global(.bmbk2pjqb) {
  fill: currentColor;
  d: path("M22 2v2H2V2zM7 10.5v3h10v-3zM2 20v2h20v-2z");
}

</style>
