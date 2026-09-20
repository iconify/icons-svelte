<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":168};
const content = `<path class="ibfzhtryg"/><path class="l6uzi97cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:htmx-icon" {...props}></Icon>
<style>
:global(.ibfzhtryg) {
  fill: var(--svg-color--111, #111);
  d: path("M181.395 42.749L256 74.204v21.858l-74.605 31.017l-5.917-21.497l55.169-20.705l-55.169-20.784zm-106.79-.001L0 74.204v21.858l74.605 31.017l5.917-21.497l-55.169-20.705l55.169-20.784z");
}

:global(.l6uzi97cb) {
  fill: var(--svg-color--4065c5, #4065c5);
  d: path("M144.34 0h25.664L112.99 167.111H85.996z");
}

</style>
