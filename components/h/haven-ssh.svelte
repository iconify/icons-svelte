<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="fmn8yub-d"><path class="rs-j0qbjd"/><path class="olxmycdzj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:haven-ssh" {...props}></Icon>
<style>
:global(.fmn8yub-d) {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.olxmycdzj) {
  d: path("M16.177 30.19L24.812 24l-8.635-6.19m11.38 11.089h5.815");
}

:global(.rs-j0qbjd) {
  d: path("M45.5 24A21.5 21.5 0 0 1 24 45.5A21.5 21.5 0 0 1 2.5 24A21.5 21.5 0 0 1 24 2.5A21.5 21.5 0 0 1 45.5 24");
}

</style>
