<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="soy222bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:flipshope" {...props}></Icon>
<style>
:global(.soy222bwl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 42.5V14.75a9.23 9.23 0 0 1 9.25-9.25H42.5M24 42.5h9.25a9.23 9.23 0 0 0 9.25-9.25V24m-12.333-2.5H17.834");
}

</style>
