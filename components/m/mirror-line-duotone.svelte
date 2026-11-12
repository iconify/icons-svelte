<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="osuf_jq5d"/><path class="n1rg9dbqj"/><path class="f_2ri90nz"/><path class="enmze0noj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mirror-line-duotone" {...props}></Icon>
<style>
:global(.enmze0noj) {
  d: path("M13 5.25604C13.9608 5.76546 14.697 6.98826 14.9257 8.50018");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.f_2ri90nz) {
  d: path("M5 20H19");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n1rg9dbqj) {
  d: path("M18 9.5C18 13.6421 15.3137 17 12 17C8.68629 17 6 13.6421 6 9.5C6 5.35786 8.68629 2 12 2C15.3137 2 18 5.35786 18 9.5Z");
}

:global(.osuf_jq5d) {
  d: path("M5 9.5V19C5 19.6491 4.78947 20.2807 4.4 20.8L3.5 22M19 9.5V19C19 19.6491 19.2105 20.2807 19.6 20.8L20.5 22");
}

</style>
