<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="cukb04b3c"/><g class="n1mjunbsu"><path class="dv_x-qb2p"/><path class="eghlyzb0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:fast-reverse-button" {...props}></Icon>
<style>
:global(.cukb04b3c) {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M63.793 56.913a6.877 6.877 0 0 1-6.878 6.882H6.875A6.88 6.88 0 0 1 0 56.913V6.877A6.877 6.877 0 0 1 6.875 0h50.041a6.876 6.876 0 0 1 6.878 6.877z");
}

:global(.dv_x-qb2p) {
  d: path("M51.938 15.04c2.305.157 4.229 1.164 5.071 2.543v27.51c-.847 1.384-2.774 2.391-5.083 2.546L29.625 31.398z");
}

:global(.eghlyzb0y) {
  d: path("M29.1 15.04c2.304.157 4.228 1.164 5.07 2.543v27.51c-.845 1.384-2.774 2.391-5.083 2.546L6.786 31.398z");
}

:global(.n1mjunbsu) {
  fill: var(--svg-color--fff, #fff);
}

</style>
