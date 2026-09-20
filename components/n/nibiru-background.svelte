<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG29Dgregb)" class="r4i437pya"/><path class="lpbji_1gz"/></g><defs><linearGradient id="SVG29Dgregb" x1=".922" x2="70.517" y1="2.277" y2="17.064" gradientUnits="userSpaceOnUse"><stop class="yqbov8bgh"/><stop offset=".13" class="nsxy5j6ft"/><stop offset=".275" class="jvfbfhz3y"/><stop offset=".395" class="j2oooab-l"/><stop offset=".52" class="bsutt-qml"/><stop offset=".66" class="srjb01h8m"/><stop offset=".8" class="l-s1yjbah"/><stop offset="1" class="rxnkilbzg"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:nibiru-background" {...props}></Icon>
<style>
:global(.bsutt-qml) {
  stop-color: var(--svg-color--82d1d9, #82d1d9);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.j2oooab-l) {
  stop-color: var(--svg-color--cdc6d7, #cdc6d7);
}

:global(.jvfbfhz3y) {
  stop-color: var(--svg-color--f2bad5, #f2bad5);
}

:global(.l-s1yjbah) {
  stop-color: var(--svg-color--11bbca, #11bbca);
}

:global(.lpbji_1gz) {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.2 4L6.836 7.773L17.2 15.306V7.517zm4.018 9.337l-7.636-5.55l3.636-2.558l4 2.813zM6.8 8.694v7.793L11.929 20l5.226-3.779zm1.018 7.26v-5.29l7.642 5.557l-3.528 2.55z");
}

:global(.nsxy5j6ft) {
  stop-color: var(--svg-color--f2a9cb, #f2a9cb);
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

:global(.rxnkilbzg) {
  stop-color: var(--svg-color--17a0bf, #17a0bf);
}

:global(.srjb01h8m) {
  stop-color: var(--svg-color--09d4d7, #09d4d7);
}

:global(.yqbov8bgh) {
  stop-color: var(--svg-color--f29ac4, #f29ac4);
}

</style>
