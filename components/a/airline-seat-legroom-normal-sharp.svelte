<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4vrpkbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:airline-seat-legroom-normal-sharp" {...props}></Icon>
<style>
:global(.x4vrpkbut) {
  fill: currentColor;
  d: path("M16 21v-7H6V3h6v6h7v9h3v3zm-2-4H3V3h2v12h9z");
}

</style>
