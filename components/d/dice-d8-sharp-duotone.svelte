<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o24dxnkiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dice-d8-sharp-duotone" {...props}></Icon>
<style>
:global(.o24dxnkiy) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2.0023L21 6.7872L21 17.2128L12 21.9977L3 17.2128L3 6.7872ZM12 2L3.3978 16.9846L20.6022 16.9846Z");
}

</style>
