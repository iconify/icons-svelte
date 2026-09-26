<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3yrkpbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:asterisk-sharp-two-tone" {...props}></Icon>
<style>
:global(.f3yrkpbxm) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4L12 20M5.6 16.8L18.4 7.2M5.6 7.2L18.4 16.8");
}

</style>
