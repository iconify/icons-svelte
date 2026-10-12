<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu8ts1b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bonfire-party-sharp" {...props}></Icon>
<style>
:global(.mu8ts1b0j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c3 2.5 5 5 5 8a5 5 0 0 1-10 0v-2.4l2-1.6l.368 1.842L11 9c-.5-2.25 0-4.25 1-6.25Zm-7.75 14l15.5 4.5m-15.5 0l15.5-4.5");
}

</style>
