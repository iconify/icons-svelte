<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jhv9elfae"/><path class="fhpdkeb_h"/><path class="vvixh7b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fineasy" {...props}></Icon>
<style>
:global(.fhpdkeb_h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 26.495l33.942-.027c-.22-5.284-3.922-11.363-11.442-11.31c-7.519.054-10.36 7.011-10.376 6.885");
}

:global(.jhv9elfae) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.006 39.635v-13.44c0-12.193 10.738-17.914 19.123-17.829c8.384.086 13.37 7.885 13.37 7.885");
}

:global(.vvixh7b4l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.805 26.486c-.043 5.888 4.146 10.974 11.387 10.963c7.24-.01 9.966-6.802 9.966-6.802");
}

</style>
