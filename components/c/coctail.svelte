<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="t3bmccb6f"/><path clip-rule="evenodd" class="za6pzxt1o"/><path class="itspgvqsh"/><path class="nk1fnt4th"/><path class="hphkf5bvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:coctail" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.hphkf5bvn) {
  d: path("M11.212 8.737a.75.75 0 1 1-1.424-.474l2.5-7.5a.75.75 0 1 1 1.423.474z");
}

:global(.itspgvqsh) {
  d: path("M11 11.5v7H9v-7z");
}

:global(.nk1fnt4th) {
  d: path("M14.5 20h-9c0-1.475 2.05-2.5 4.5-2.5s4.5 1.025 4.5 2.5M12.818 1.728a.75.75 0 0 1 .364-1.456l4 1a.75.75 0 0 1-.364 1.456z");
}

:global(.t3bmccb6f) {
  d: path("M6 8a.5.5 0 0 1 0-1h8a.5.5 0 0 1 0 1z");
}

:global(.za6pzxt1o) {
  fill-rule: evenodd;
  d: path("m2.767 5.68l6.5 7a1 1 0 0 0 1.466 0l6.5-7c.594-.64.14-1.68-.733-1.68h-13c-.873 0-1.327 1.04-.733 1.68m11.44.32L10 10.53L5.793 6z");
}

</style>
