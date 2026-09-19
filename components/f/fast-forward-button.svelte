<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="e72jvsl3w"/><g class="n1mjunbsu"><path class="cs493vb3v"/><path class="nj514j4pu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:fast-forward-button" {...props}></Icon>
<style>
:global(.cs493vb3v) {
  d: path("M11.899 15.1c-2.313.157-4.245 1.168-5.091 2.553v27.618c.85 1.388 2.786 2.4 5.103 2.554l22.39-16.303z");
}

:global(.e72jvsl3w) {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M64 57.1a6.9 6.9 0 0 1-6.896 6.903H6.894A6.9 6.9 0 0 1-.002 57.1V6.9A6.9 6.9 0 0 1 6.894.001h50.21C60.914.001 64 3.091 64 6.9z");
}

:global(.n1mjunbsu) {
  fill: var(--svg-color--fff, #fff);
}

:global(.nj514j4pu) {
  d: path("M34.831 15.1c-2.313.157-4.245 1.168-5.09 2.553v27.618c.85 1.388 2.785 2.4 5.103 2.554l22.39-16.303z");
}

</style>
