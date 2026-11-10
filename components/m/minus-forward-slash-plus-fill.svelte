<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad3-4d-lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:minus-forward-slash-plus-fill" {...props}></Icon>
<style>
:global(.ad3-4d-lf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 18H17.9986M17.9986 18H22M17.9986 18L17.9971 22M17.9986 18L18 14M2 6H10M5 22L19 2");
}

</style>
