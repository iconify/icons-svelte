<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="we1qbbcss"/><path clip-rule="evenodd" class="lmkh4gsgw"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:flag-straight-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.lmkh4gsgw) {
  fill-rule: evenodd;
  d: path("M3.5 3a1 1 0 0 1 1 1v13a1 1 0 1 1-2 0V4a1 1 0 0 1 1-1");
}

:global(.we1qbbcss) {
  fill-rule: evenodd;
  d: path("M4.5 4v6h10.159l-1.197-1.71a2.25 2.25 0 0 1 0-2.58L14.659 4zm-1-2a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h13.08a1 1 0 0 0 .819-1.573L15.1 7.143a.25.25 0 0 1 0-.286l2.3-3.284A1 1 0 0 0 16.579 2z");
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
