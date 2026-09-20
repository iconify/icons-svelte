<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zu4ajq05m"/><path class="kd69mvbqa"/><path class="va4lqxm9h"/><path class="fqg-d6bob"/><path class="plef9ibei"/><path class="z15-ixbci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:failover-region-outline-regular" {...props}></Icon>
<style>
:global(.fqg-d6bob) {
  d: path("M14 17.5h7");
}

:global(.kd69mvbqa) {
  d: path("m4 9 5 -5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.plef9ibei) {
  d: path("M17.5 14v7");
}

:global(.va4lqxm9h) {
  d: path("M13.5 17.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.z15-ixbci) {
  d: path("M9.5 9.5 14 14");
}

:global(.zu4ajq05m) {
  d: path("M2.5 6.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
