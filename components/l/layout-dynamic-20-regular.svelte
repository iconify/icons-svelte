<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fkynqqajv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-dynamic-20-regular" {...props}></Icon>
<style>
:global(.fkynqqajv) {
  fill: currentColor;
  d: path("M14 3a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3zM4 14a2 2 0 0 0 2 2h1v-3H4zm4 2h6a2 2 0 0 0 2-2v-1H8zM6 4a2 2 0 0 0-2 2v6h3V4zm2 8h8V6a2 2 0 0 0-2-2H8z");
}

</style>
