<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sn_67ybko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:breakout-room-32-filled" {...props}></Icon>
<style>
:global(.sn_67ybko) {
  fill: currentColor;
  d: path("M7.5 3A4.5 4.5 0 0 0 3 7.5v6.031A6 6 0 0 1 7.5 11.5h7a6 6 0 0 1 6 6v7c0 1.792-.786 3.4-2.031 4.5H24.5a4.5 4.5 0 0 0 4.5-4.5v-17A4.5 4.5 0 0 0 24.5 3zM3 17.5A4.5 4.5 0 0 1 7.5 13h7a4.5 4.5 0 0 1 4.5 4.5v7a4.5 4.5 0 0 1-4.5 4.5h-7A4.5 4.5 0 0 1 3 24.5z");
}

</style>
