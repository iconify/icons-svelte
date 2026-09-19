<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epegidc8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-start" {...props}></Icon>
<style>
:global(.epegidc8d) {
  fill: currentColor;
  d: path("M14.59 7.41L18.17 11H6v2h12.17l-3.59 3.59L16 18l6-6l-6-6zM2 6v12h2V6z");
}

</style>
