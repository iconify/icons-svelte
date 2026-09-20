<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b6aozgbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:quad" {...props}></Icon>
<style>
:global(.b6aozgbpa) {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.2 4.8H4.8v14.4h13.128l-3-3H7.8V7.8h8.4v7.128l3 3zM3 3v18h18V3zm6.6 6.6h4.8v4.8H9.6z");
}

</style>
