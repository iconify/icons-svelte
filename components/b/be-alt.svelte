<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oq-_vfudf"/><g class="y9tr6bcfx"><path class="oyd_cmbnp"/><path class="jah-39b7q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:be-alt" {...props}></Icon>
<style>
:global(.jah-39b7q) {
  d: path("M31.314 21.374a10.5 10.5 0 0 1-2.717 20.643m-.8-36.033a7.125 7.125 0 0 1-2.202 13.901");
}

:global(.oq-_vfudf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.596 10.885l-1.425 9m-1.307 9.751l-1.96 12.379m4.692-31.129h9.75m-11.175 9h13.425m-14.732 9.75h14.732M8.903 42.016h19.693");
}

:global(.oyd_cmbnp) {
  d: path("M27.797 5.984c0 2.486-1.966 4.902-4.451 4.902m7.968 10.488c.483 1.802.178 4.435-.957 5.915a6 6 0 0 1-4.76 2.347");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
