<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="fwtwsacfh"/><path class="hxpu3kbqp"/><path class="ergimzbtk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:open-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ergimzbtk) {
  d: path("M12 5a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2zM1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

:global(.fwtwsacfh) {
  d: path("M10.707 10.707a1 1 0 0 1-1.414-1.414l6-6a1 1 0 1 1 1.414 1.414z");
}

:global(.hxpu3kbqp) {
  d: path("M15 15v-3.5a1 1 0 1 1 2 0V16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h4.5a1 1 0 0 1 0 2H5v10zm2-7a1 1 0 1 1-2 0V4a1 1 0 1 1 2 0z");
}

</style>
