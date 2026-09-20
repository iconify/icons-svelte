<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="zy2jsybir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:number-four-light" {...props}></Icon>
<style>
:global(.zy2jsybir) {
  fill: currentColor;
  d: path("M184 162h-18V48a6 6 0 0 0-10.69-3.75l-96 120A6 6 0 0 0 64 174h90v34a6 6 0 0 0 12 0v-34h18a6 6 0 0 0 0-12m-30 0H76.48L154 65.1Z");
}

</style>
