<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns34tgboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-to-line" {...props}></Icon>
<style>
:global(.ns34tgboy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2V17.059M19 11.123L12.4125 17.826C12.1847 18.058 11.8153 18.058 11.5875 17.826L5 11.123M19 22H5");
}

</style>
