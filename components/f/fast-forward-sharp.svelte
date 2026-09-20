<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccpxfdb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:fast-forward-sharp" {...props}></Icon>
<style>
:global(.ccpxfdb4y) {
  fill: currentColor;
  d: path("M2.5 18V6l9 6zm10 0V6l9 6z");
}

</style>
