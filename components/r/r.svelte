<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGc6YqvdTJ)" class="uzhbyubok"/><defs><linearGradient id="SVGc6YqvdTJ" x1="7.682" x2="19.229" y1="6.198" y2="15.195" gradientUnits="userSpaceOnUse"><stop class="zj1_afigk"/><stop offset="1" class="ewsnj8t9d"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:r" {...props}></Icon>
<style>
:global(.ewsnj8t9d) {
  stop-color: var(--svg-color--3a0c4c, #3a0c4c);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.uzhbyubok) {
  d: path("M9.187 18.75V6.795l4.994 2.783l-3.869 2.036v3.76L18.187 21v-4.077l-4.584-3.277l4.022-2.111v-3.77L9.187 3L5.813 4.687V21z");
}

:global(.zj1_afigk) {
  stop-color: var(--svg-color--771a4e, #771a4e);
}

</style>
