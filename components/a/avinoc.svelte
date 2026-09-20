<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1mjunbsu"><path class="dnnn5h5pq"/><path class="k3j_vhiyn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:avinoc" {...props}></Icon>
<style>
:global(.dnnn5h5pq) {
  d: path("M7.373 4.059h7.2L11.74 5.647H8.4L4.8 12l3.6 6.353h7.2L18.94 12L17.4 9.353l.26-3.177L21 12l-4.373 7.941H7.373L3 12z");
}

:global(.k3j_vhiyn) {
  d: path("m7.373 10.412l9.513-6.353L15.6 15.176l-2.573-4.764z");
}

:global(.n1mjunbsu) {
  fill: var(--svg-color--fff, #fff);
}

</style>
