<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="n-ltlnb2x"/><path class="fasksccxm"/><path class="m21k70b4x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:auto-background" {...props}></Icon>
<style>
:global(.beaf9ac8r) {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

:global(.fasksccxm) {
  fill: var(--svg-color--109e92, #109e92);
  d: path("M11.259 6.103L6.629 8.91v5.417l4.63-2.694z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.m21k70b4x) {
  fill: var(--svg-color--000, #000);
  d: path("m18.737 14.614l-2.947-1.845v-1.584l1.263.673V8.952l-4.211-2.737v6.205l-1.257.718l5.975 3.576L12 20l-6.738-3.982V8.053L12 4l6.737 4.053zM6.947 8.952v5.182l4.21-2.56V6.32zm3.083 5.075l-2.487 1.536L12 18.196l2.517-1.488z");
}

:global(.n-ltlnb2x) {
  fill: var(--svg-color--e9595c, #e9595c);
  d: path("m7.315 15.524l2.687-1.683l4.78 2.842l-2.677 1.719z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
