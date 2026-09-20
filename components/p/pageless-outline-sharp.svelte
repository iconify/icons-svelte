<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzc-1ofzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:pageless-outline-sharp" {...props}></Icon>
<style>
:global(.wzc-1ofzr) {
  fill: currentColor;
  d: path("M1 22v-8h2v6h7v2zm13 0v-2h7v-6h2v8zM1 10V2h9v2H3v6zm20 0V4h-7V2h9v8z");
}

</style>
