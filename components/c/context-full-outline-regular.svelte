<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="y5k8b5bfa"/><path class="l517yxbln"/><path class="coi-np7dk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-full-outline-regular" {...props}></Icon>
<style>
:global(.b4x_isbqv) {
  d: path("M8 6H5v12h3");
}

:global(.coi-np7dk) {
  d: path("M15 9v6");
}

:global(.d_6ujebpi) {
  d: path("M16 6h3v12h-3");
}

:global(.l517yxbln) {
  d: path("M12 9v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y5k8b5bfa) {
  d: path("M9 9v6");
}

</style>
