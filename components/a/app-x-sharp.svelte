<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gos3aq1fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:app-x-sharp" {...props}></Icon>
<style>
:global(.gos3aq1fi) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21L3 21L3 3L21 3L21 12M14.7071 14.7071L21.2929 21.2929M21.2929 14.7071L14.7071 21.2929");
}

</style>
