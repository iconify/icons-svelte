<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y7ooxjbpw"/><path class="atynmcc4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:conflux" {...props}></Icon>
<style>
:global(.atynmcc4u) {
  fill: var(--svg-color--37a1db, #37a1db);
  d: path("M19.2 10.255L12.01 3L4.8 10.275l.023 3.4l7.156-7.22l7.209 7.273z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.y7ooxjbpw) {
  fill: var(--svg-color--fff, #fff);
  d: path("m15.803 13.727l-3.807 3.84l-2.118-2.138l3.807-3.84l-1.694-1.709l-5.517 5.568L11.976 21l5.519-5.567z");
}

</style>
