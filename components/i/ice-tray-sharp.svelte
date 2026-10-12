<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4hk_5bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ice-tray-sharp" {...props}></Icon>
<style>
:global(.w4hk_5bvo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 11.25h16.5v10H3.75zm0 5h16.5m-8.25-5v10m1.57-17.9l2.16-.45l1.17-.25l.25 1.17l.45 2.16l.25 1.17l-1.17.25l-2.16.45l-1.17.25l-.25-1.17l-.45-2.16l-.25-1.17z");
}

</style>
