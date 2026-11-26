<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="reriojkya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:layers-check-sharp" {...props}></Icon>
<style>
:global(.reriojkya) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2L22 7.5L12 13L2 7.5ZM1.4819 11.7151L12.2251 17.6238M1.4819 16.2151L12.2251 22.1238M16.7071 19.2071L18.6667 21.1667L22 17.8333L22.2929 17.5404");
}

</style>
