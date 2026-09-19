<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<g transform="translate(.11 5.498)" class="dblf6lbtm"><ellipse class="nz6tgldhc"/><ellipse class="bazrq7baw"/><ellipse class="znp-ktptm"/><ellipse class="vqfr1mkcv"/><ellipse class="j0t1embal"/><ellipse class="js9ufp85k"/><ellipse class="tk7i63bri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:left-thought-bubble" {...props}></Icon>
<style>
:global(.bazrq7baw) {
  cx: 56.946px;
  cy: 50.909px;
  rx: 2.893px;
  ry: 2.235px;
}

:global(.dblf6lbtm) {
  fill: var(--svg-color--97d8ea, #97d8ea);
}

:global(.j0t1embal) {
  cx: 28.833px;
  cy: 12.428px;
  rx: 18.02px;
  ry: 9.893px;
}

:global(.js9ufp85k) {
  cx: 30.06px;
  cy: 29.25px;
  rx: 18.02px;
  ry: 9.893px;
}

:global(.nz6tgldhc) {
  cx: 49.46px;
  cy: 44.28px;
  rx: 4.592px;
  ry: 3.739px;
}

:global(.tk7i63bri) {
  cx: 16.99px;
  cy: 27.01px;
  rx: 17.1px;
  ry: 9.423px;
}

:global(.vqfr1mkcv) {
  cx: 28.832px;
  cy: 13.299px;
  rx: 23.521px;
  ry: 13.994px;
}

:global(.znp-ktptm) {
  cx: 46.85px;
  cy: 24.31px;
  rx: 16.787px;
  ry: 12.23px;
}

</style>
