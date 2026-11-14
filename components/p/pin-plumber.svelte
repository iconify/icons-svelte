<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctu-_ogcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-plumber" {...props}></Icon>
<style>
:global(.ctu-_ogcq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.338 18.187l8.132-8.132l2.475 2.475l-8.132 8.132Zm8.132-8.132l-.354-3.182l3.889-3.889l1.945 1.945l-2.122 2.121l2.122 2.122l2.121-2.122l1.945 1.945l-3.889 3.889l-3.182-.354Z");
}

</style>
