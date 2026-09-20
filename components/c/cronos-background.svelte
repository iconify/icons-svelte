<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bunnh2o0p"/><path class="b-apsi6ej"/><path class="wvy6nbcgq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:cronos-background" {...props}></Icon>
<style>
:global(.b-apsi6ej) {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.003 4L5 8.001v8L12.003 20L19 16.001v-8zm4.924 10.816l-4.924 2.813l-4.927-2.813V9.184l4.927-2.813l4.924 2.813z");
}

:global(.bunnh2o0p) {
  fill: var(--svg-color--051221, #051221);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.wvy6nbcgq) {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.267 13.87L12 15.737L8.728 13.87v-3.736l3.271-1.87l3.268 1.87l-1.36.778l-1.908-1.092l-1.908 1.092v2.177L12 14.182l1.908-1.091z");
}

</style>
