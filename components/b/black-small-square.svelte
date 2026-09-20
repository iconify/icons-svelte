<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="t1-2mybuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:black-small-square" {...props}></Icon>
<style>
:global(.t1-2mybuz) {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M25 24a1 1 0 0 1-1 1H12a1 1 0 0 1-1-1V12a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1z");
}

</style>
