<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="pk07sfbhl"/><path class="bpn-oncsg"/><path class="ufkek0beu"/><path class="wc3mi9f0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:flag-for-flag-myanmar" {...props}></Icon>
<style>
:global(.bpn-oncsg) {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M32 2C18.9 2 7.8 10.4 3.7 22h56.6C56.2 10.4 45.1 2 32 2");
}

:global(.pk07sfbhl) {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 62c13.1 0 24.2-8.3 28.3-20H3.7C7.8 53.7 18.9 62 32 62");
}

:global(.ufkek0beu) {
  fill: var(--svg-color--699635, #699635);
  d: path("M60.3 42c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10H3.7C2.6 25.1 2 28.5 2 32s.6 6.9 1.7 10z");
}

:global(.wc3mi9f0k) {
  fill: var(--svg-color--fff, #fff);
  d: path("M32 41.1L43.7 50l-4.4-14.5l11.7-9H36.5L32 12l-4.5 14.5H13l11.7 9L20.3 50z");
}

</style>
