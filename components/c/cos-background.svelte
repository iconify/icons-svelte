<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGucLjpMKr)" class="r4i437pya"/><path class="hu1lx9dvg"/><path class="kg9cp1bbd"/><path class="ylu9c_bek"/></g><defs><linearGradient id="SVGucLjpMKr" x1="13.601" x2="12.507" y1="4" y2="11.762" gradientUnits="userSpaceOnUse"><stop class="m6oxpybpp"/><stop offset="1" class="gcy142b3s"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:cos-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.gcy142b3s) {
  stop-color: var(--svg-color--2797fd, #2797fd);
}

:global(.hu1lx9dvg) {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.927 4c3.185 0 5.39 1.945 6.15 2.99c-.615.855-2.29 1.155-3.605.455a5.5 5.5 0 0 0-2.545-.67c-2.78 0-4.37 2.115-4.82 3.225h-2.9c1.115-3.6 4.045-6 7.72-6m.021 16c3.185 0 5.39-1.945 6.15-2.99c-.615-.86-2.295-1.155-3.61-.455a5.5 5.5 0 0 1-2.54.67c-2.78 0-4.37-2.115-4.82-3.225h-2.9c1.11 3.6 4.045 6 7.72 6");
}

:global(.kg9cp1bbd) {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.192 17.12A4.43 4.43 0 0 1 5.202 14h2.915a5.34 5.34 0 0 0 4.785 3.225c-.75.2-2.72.49-4.71-.105m-.02-10.24A4.43 4.43 0 0 0 5.187 10h2.915c1.2-2.636 3.7-3.26 4.8-3.226c-.75-.2-2.735-.49-4.73.105M6.902 13.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

:global(.m6oxpybpp) {
  stop-color: var(--svg-color--0dc4fa, #0dc4fa);
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

:global(.ylu9c_bek) {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.402 13.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

</style>
