<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n7xd0hbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:metrolist" {...props}></Icon>
<style>
:global(.n7xd0hbyt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.44 26.696l-5.063 5.062a2.557 2.557 0 0 0 0 3.617l6.377 6.376a2.557 2.557 0 0 0 3.616 0l7.436-7.435c.48-.48.749-1.13.749-1.809V7.33c0-1.626 1.966-2.44 3.116-1.29l10.7 10.7");
}

</style>
