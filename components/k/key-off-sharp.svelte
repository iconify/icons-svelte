<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fch5k7bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:key-off-sharp" {...props}></Icon>
<style>
:global(.fch5k7bud) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12C10 14.2091 8.2091 16 6 16C3.7909 16 2 14.2091 2 12C2 9.7909 3.7909 8 6 8C8.2091 8 10 9.7909 10 12ZM10 12L12 12M16.6569 12L17.6569 12L23 12M21 12L21 15.3431L21 16.3431M1.7071 1.7071L22.2929 22.2929");
}

</style>
