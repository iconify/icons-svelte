<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="d2e4k2bdf"/><path class="odcrtlbrp"/><path class="cw5q1-brs"/><path class="mu5xvwl5p"/><path fill="url(#SVGmam9EdKg)" class="ph4ggjbwq"/></g><defs><linearGradient id="SVGmam9EdKg" x1="14.649" x2="7.925" y1="9.458" y2="14.832" gradientUnits="userSpaceOnUse"><stop class="f_idz2bjc"/><stop offset=".42" class="ncuebz6vy"/><stop offset=".65" class="lyl1xqb_w"/><stop offset="1" class="az_osfwxl"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:dione-background" {...props}></Icon>
<style>
:global(.az_osfwxl) {
  stop-color: var(--svg-color--688feb, #688feb);
}

:global(.beaf9ac8r) {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

:global(.cw5q1-brs) {
  fill: var(--svg-color--fb88f3, #fb88f3);
  d: path("M12 16.982a4.982 4.982 0 1 0 0-9.965a4.982 4.982 0 0 0 0 9.965");
}

:global(.d2e4k2bdf) {
  fill: var(--svg-color--30128d, #30128d);
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

:global(.f_idz2bjc) {
  stop-color: var(--svg-color--6ddff4, #6ddff4);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.lyl1xqb_w) {
  stop-color: var(--svg-color--20dffb, #20dffb);
}

:global(.mu5xvwl5p) {
  fill: var(--svg-color--e7b2f8, #e7b2f8);
  d: path("M12 16.586a4.587 4.587 0 1 0 0-9.173a4.587 4.587 0 0 0 0 9.173");
}

:global(.ncuebz6vy) {
  stop-color: var(--svg-color--10fdf7, #10fdf7);
}

:global(.odcrtlbrp) {
  fill: var(--svg-color--7d1fa9, #7d1fa9);
  d: path("M12 18.586a6.587 6.587 0 1 0 0-13.173a6.587 6.587 0 0 0 0 13.173");
}

:global(.ph4ggjbwq) {
  d: path("M16.054 12.152c0 2.31-1.547 3.333-3.818 3.915c-1.01.262-1.854.147-2.591 0c-1.183-.235-1.818-1.066-2.165-2.222a3 3 0 0 1-.093-.88c0-1.676 2.186-4.987 4.489-4.987a4.18 4.18 0 0 1 4.178 4.178z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
