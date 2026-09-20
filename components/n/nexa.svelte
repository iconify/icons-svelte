<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="neiui2ems"/><path class="wpsy_t-hm"/><path class="n-b3qobhv"/><path class="l0bnbxbdr"/><path class="wdunz5bct"/><path class="innhbzbif"/><path class="xekk8j_yl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:nexa" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.innhbzbif) {
  fill: var(--svg-color--b6761c, #b6761c);
  d: path("M11.999 7.279L7.764 3.266l4.235 6.882z");
}

:global(.l0bnbxbdr) {
  fill: var(--svg-color--b6761c, #b6761c);
  d: path("M15.705 8.03H8.293l3.706 3.705z");
}

:global(.n-b3qobhv) {
  fill: var(--svg-color--ffe144, #ffe144);
  d: path("M21 5.911H3l9 9.53z");
}

:global(.neiui2ems) {
  fill: var(--svg-color--fffd9d, #fffd9d);
  d: path("m12 15.44l9-9.529l-9 14.824z");
}

:global(.wdunz5bct) {
  fill: var(--svg-color--fffd9d, #fffd9d);
  d: path("m12 7.279l4.235-4.013L12 10.148z");
}

:global(.wpsy_t-hm) {
  fill: var(--svg-color--b6761c, #b6761c);
  d: path("M12 15.44L3 5.911l9 14.824z");
}

:global(.xekk8j_yl) {
  fill: var(--svg-color--ffe144, #ffe144);
  d: path("M16.234 3.266h-8.47l4.235 4.013z");
}

</style>
