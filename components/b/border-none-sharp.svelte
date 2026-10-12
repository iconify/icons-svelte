<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpx7i6bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:border-none-sharp" {...props}></Icon>
<style>
:global(.tpx7i6bbm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h.01M3 7.5h.01M3 12h.01M3 16.5h.01M3 21h.01M7.5 3h.01M7.5 21h.01M12 3h.01M12 21h.01M16.5 3h.01m-.01 18h.01M21 3h.01M21 7.5h.01M21 12h.01M21 16.5h.01M21 21h.01M7.5 12h.01M12 7.5h.01M12 12h.01M12 16.5h.01M16.5 12h.01");
}

</style>
