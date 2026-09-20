<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr5bbb6od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:label-sharp" {...props}></Icon>
<style>
:global(.rr5bbb6od) {
  fill: currentColor;
  d: path("M2 20V4h14l6 8l-6 8z");
}

</style>
