<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngm2qlbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-insert-outline-sharp" {...props}></Icon>
<style>
:global(.ngm2qlbef) {
  fill: currentColor;
  d: path("M17.6 18L8 8.4V17H6V5h12v2H9.4l9.6 9.6z");
}

</style>
