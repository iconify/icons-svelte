<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lppkb600w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-left-alt-outline-sharp" {...props}></Icon>
<style>
:global(.lppkb600w) {
  fill: currentColor;
  d: path("m10 18l-6-6l6-6l1.4 1.45L7.85 11H20v2H7.85l3.55 3.55z");
}

</style>
