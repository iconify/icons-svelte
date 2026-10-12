<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-patz2ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:color-picker" {...props}></Icon>
<style>
:global(.g-patz2ff) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.66 4.75l-1.41-1.41q-.71-.71-1.42 0l-.7.7q-.71.71 0 1.42l1.41 1.41q.71.71 1.42 0l.7-.7q.71-.71 0-1.42m-2.83 1.42l-2.12 2.12m2.06 2.05l-4.11-4.11q-.42-.42-.84 0l-.58.58q-.42.42.01.84l.38.39q.43.42.01.84l-6.41 6.41q-.42.42-.57 1l-.58 2.2q-.15.58.43.43l2.2-.58q.58-.15 1-.57l6.41-6.41q.42-.42.84.01l.39.38q.42.43.84.01l.58-.58q.42-.42 0-.84");
}

</style>
