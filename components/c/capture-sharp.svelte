<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsr9ewboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:capture-sharp" {...props}></Icon>
<style>
:global(.lsr9ewboa) {
  fill: currentColor;
  d: path("M6 16h12V8H6zm-4 4V4h20v16z");
}

</style>
