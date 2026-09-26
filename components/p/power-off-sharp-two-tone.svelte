<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ky8hevb5b"/><path class="ahhqo1b4s"/><path class="icotk-bsx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:power-off-sharp-two-tone" {...props}></Icon>
<style>
:global(.ahhqo1b4s) {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.icotk-bsx) {
  stroke-opacity: 0.4;
  d: path("M15.0835 2.4348L16 2.8348C19.6443 4.4253 22 8.0238 22 12C22 13.2499 21.7657 14.4887 21.3092 15.6523L20.944 16.5832M12 1L12 7.3431");
}

:global(.ky8hevb5b) {
  stroke-opacity: 0.4;
  d: path("M19.0711 19.0711C17.1957 20.9464 14.6522 22 12 22C6.4772 22 2 17.5228 2 12C2 9.3478 3.0536 6.8043 4.9289 4.9289");
}

</style>
