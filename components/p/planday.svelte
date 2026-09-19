<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kr120406v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:planday" {...props}></Icon>
<style>
:global(.kr120406v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 34.367l12.315-14.49m13.406 9.7c6.83-8.769-4.973-20.004-13.406-9.7m13.406 9.7c-4.858 4.858-10.44 2.327-13.05-.737m13.272.46L43.5 13.634");
}

</style>
