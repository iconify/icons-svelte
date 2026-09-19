<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ib5218msv"/><path class="vbpytgzkx"/><path class="egjivnbzm"/><path class="atmpwmb_a"/><path class="dr6-7m50k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:alien" {...props}></Icon>
<style>
:global(.atmpwmb_a) {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M41.21 28.554c-6.688 9.148-9.1 18.74-5.407 21.445c3.704 2.704 12.11-2.512 18.794-11.659c6.681-9.14 9.107-18.739 5.405-21.448c-3.698-2.701-12.12 2.527-18.792 11.662");
}

:global(.dr6-7m50k) {
  fill: var(--svg-color--d1d2d2, #d1d2d2);
  d: path("M46.11 28.999c-3.89 5.321-5.295 10.904-3.146 12.478c2.154 1.572 7.04-1.461 10.937-6.786c3.886-5.316 5.299-10.902 3.145-12.478c-2.152-1.571-7.05 1.469-10.936 6.786");
}

:global(.egjivnbzm) {
  fill: var(--svg-color--d1d2d2, #d1d2d2);
  d: path("M19.557 29.02c3.89 5.323 5.294 10.904 3.147 12.479c-2.156 1.574-7.04-1.462-10.936-6.782c-3.888-5.321-5.299-10.904-3.145-12.483c2.151-1.57 7.05 1.472 10.934 6.786");
}

:global(.ib5218msv) {
  fill: var(--svg-color--93bbc5, #93bbc5);
  d: path("M63.361 21.857C63.361 9.778 49.634 0 32.681 0S2 9.778 2 21.857c0 12.067 13.729 41.832 30.681 41.832c16.953-.001 30.68-29.765 30.68-41.832");
}

:global(.vbpytgzkx) {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M23.983 28.554c6.687 9.148 9.1 18.74 5.407 21.445c-3.704 2.704-12.11-2.512-18.794-11.659c-6.68-9.14-9.107-18.739-5.405-21.448c3.698-2.701 12.11 2.527 18.792 11.662");
}

</style>
