<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="x3ijfacgt"/><path class="rakwf0bjj"/><path class="cm1-zsbfq"/><path class="k_no2cbtc"/><path class="lp6l87b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:gem-stone" {...props}></Icon>
<style>
:global(.cm1-zsbfq) {
  fill: var(--svg-color--4289c1, #4289c1);
  d: path("M26 12h10L18 33z");
}

:global(.k_no2cbtc) {
  fill: var(--svg-color--8ccaf7, #8ccaf7);
  d: path("M10 12H0l18 21zm3-9l-3 9h16l-3-9z");
}

:global(.lp6l87b0h) {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("m18 33l-8-21h16z");
}

:global(.rakwf0bjj) {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("m36 12l-7-9h-6l3 9z");
}

:global(.x3ijfacgt) {
  fill: var(--svg-color--bdddf4, #bdddf4);
  d: path("M13 3H7l-7 9h10z");
}

</style>
