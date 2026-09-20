<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hscoo02qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:line-end-diamond-sharp" {...props}></Icon>
<style>
:global(.hscoo02qk) {
  fill: currentColor;
  d: path("m15 19l-6-6H2v-2h7l6-6l7 7z");
}

</style>
