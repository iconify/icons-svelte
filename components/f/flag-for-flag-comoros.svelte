<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="jm690d9gm"/><path class="ieadtccpw"/><path class="fmxdj6b4y"/><path class="dhd_xvbxt"/><path class="ag4fbobtr"/><g class="md286fbip"><path class="amfldab_q"/><path class="hk_cfg4zv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-flag-comoros" {...props}></Icon>
<style>
:global(.ag4fbobtr) {
  fill: var(--svg-color--3d8e33, #3D8E33);
  d: path("M1.351 6.004H1.35A3.991 3.991 0 0 0 0 9v18c0 1.193.522 2.264 1.351 2.997L17.5 18L1.351 6.004z");
}

:global(.amfldab_q) {
  d: path("M3.926 18a5.52 5.52 0 0 1 4.295-5.38a5.514 5.514 0 0 0-1.227-.142a5.522 5.522 0 1 0 0 11.044c.422 0 .832-.052 1.227-.142A5.52 5.52 0 0 1 3.926 18z");
}

:global(.dhd_xvbxt) {
  fill: var(--svg-color--eee, #EEE);
  d: path("M0 11.5h36V18H0z");
}

:global(.fmxdj6b4y) {
  fill: var(--svg-color--ce1126, #CE1126);
  d: path("M0 18h36v6.5H0z");
}

:global(.hk_cfg4zv) {
  d: path("M7.62 14.875l.601-.437l.601.437l-.23-.706l.601-.437H8.45l-.229-.707l-.23.707h-.743l.601.437zm0 2.635l.601-.437l.601.437l-.23-.707l.601-.436H8.45l-.229-.707l-.23.707h-.743l.601.436zm0 2.635l.601-.437l.601.437l-.23-.707l.601-.437H8.45l-.229-.706l-.23.706h-.743l.601.437zm.601 2.198l.601.436l-.23-.706l.601-.437H8.45l-.229-.706l-.23.706h-.743l.601.437l-.229.706z");
}

:global(.ieadtccpw) {
  fill: var(--svg-color--ffc61e, #FFC61E);
  d: path("M36 18V9a4 4 0 0 0-4-4H4a4 4 0 0 0-4 4v9h36z");
}

:global(.jm690d9gm) {
  fill: var(--svg-color--3a75c4, #3A75C4);
  d: path("M0 18v9a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-9H0z");
}

:global(.md286fbip) {
  fill: var(--svg-color--fff, #FFF);
}

</style>
