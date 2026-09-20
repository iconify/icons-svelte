<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmin4jbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crop-21-9-outline-sharp" {...props}></Icon>
<style>
:global(.tmin4jbct) {
  fill: currentColor;
  d: path("M2 17V7h20v10zm2-2h16V9H4zm0 0V9z");
}

</style>
