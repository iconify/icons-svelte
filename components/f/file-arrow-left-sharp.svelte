<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez27hhb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-arrow-left-sharp" {...props}></Icon>
<style>
:global(.ez27hhb1c) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 2L4 2L4 22L11 22M14 2L20 8L20 13M14 2L14 8L20 8M21 19L14 19M17.2929 15.7071L14 19L17.2929 22.2929");
}

</style>
