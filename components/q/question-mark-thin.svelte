<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="q-g3lnbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:question-mark-thin" {...props}></Icon>
<style>
:global(.q-g3lnbce) {
  fill: currentColor;
  d: path("M188 96c0 27.51-24.77 50.09-56 51.89V160a4 4 0 0 1-8 0v-16a4 4 0 0 1 4-4c28.67 0 52-19.74 52-44s-23.33-44-52-44s-52 19.74-52 44a4 4 0 0 1-8 0c0-28.67 26.92-52 60-52s60 23.33 60 52m-60 100a12 12 0 1 0 12 12a12 12 0 0 0-12-12");
}

</style>
