<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ho4ovebol"/><path class="ro2r52bxw"/><path class="b13a6fbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-taskfile" {...props}></Icon>
<style>
:global(.b13a6fbul) {
  fill: var(--svg-color--94ded7, #94ded7);
  d: path("M16.002 16.256L4.252 9.133l11.75-7.12l11.747 7.12z");
}

:global(.ho4ovebol) {
  fill: var(--svg-color--28bdb0, #28bdb0);
  d: path("M16.002 16.256v13.73l-11.75-7.12V9.132z");
}

:global(.ro2r52bxw) {
  fill: var(--svg-color--68d1c7, #68d1c7);
  d: path("M16.002 16.256v13.73l11.747-7.12V9.132z");
}

</style>
