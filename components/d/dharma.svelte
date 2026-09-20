<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f88dycc6g"/><path class="uh13e0blc"/><path class="bwjd9fbbn"/><path class="id_jai1yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dharma" {...props}></Icon>
<style>
:global(.bwjd9fbbn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.819 28.922za5.29 5.29 0 0 1 5.29 5.29V42.5h-10.58v-8.288a5.29 5.29 0 0 1 5.29-5.29");
}

:global(.f88dycc6g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5zA18.5 18.5 0 0 1 42.5 24v16.5a2 2 0 0 1-2 2h-33a2 2 0 0 1-2-2V24A18.5 18.5 0 0 1 24 5.5");
}

:global(.id_jai1yr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.546 20.427za9.636 9.636 0 0 1 9.636 9.636V42.5H15.91V30.063a9.636 9.636 0 0 1 9.636-9.636");
}

:global(.uh13e0blc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.83 11.384za13.465 13.465 0 0 1 13.465 13.465V42.5h-26.93V24.849A13.465 13.465 0 0 1 23.83 11.384");
}

</style>
