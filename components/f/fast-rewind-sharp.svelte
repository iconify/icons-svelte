<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n32iw0bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:fast-rewind-sharp" {...props}></Icon>
<style>
:global(.n32iw0bmf) {
  fill: currentColor;
  d: path("m21.5 18l-9-6l9-6zm-10 0l-9-6l9-6z");
}

</style>
