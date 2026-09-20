<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3-tvrbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:label-important-outline-sharp" {...props}></Icon>
<style>
:global(.z3-tvrbfs) {
  fill: currentColor;
  d: path("m2 20l6-8l-6-8h14l6 8l-6 8zm4-2h9l4.5-6L15 6H6l4.5 6zm6.75-6");
}

</style>
