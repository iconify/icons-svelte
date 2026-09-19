<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="os7g2fb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ombi" {...props}></Icon>
<style>
:global(.os7g2fb3h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.396 22.492a5.725 5.725 0 0 0 8.096-8.096l-7.22-7.22a5.725 5.725 0 0 0-8.095 8.097zm18.331 18.331a5.725 5.725 0 0 0 8.096-8.096l-7.22-7.22a5.725 5.725 0 0 0-8.095 8.097zM16.218 16.218l15.564 15.564m-.384-15.18l3.704-3.704m-2.633 6.743h5.111m-9.189-3.703v-5.579");
}

</style>
