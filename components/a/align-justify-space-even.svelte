<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_-ycebyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-justify-space-even" {...props}></Icon>
<style>
:global(.y_-ycebyf) {
  fill: currentColor;
  d: path("M20 22V2h2v20zM2 22V2h2v20zm12-5V7h3v10zm-7 0V7h3v10z");
}

</style>
