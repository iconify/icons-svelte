<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="xf78a_b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:heavy-check-mark" {...props}></Icon>
<style>
:global(.xf78a_b-m) {
  fill: var(--svg-color--4d5357, #4d5357);
  d: path("M56 2L18.8 42.9L8 34.7H2L18.8 62L62 2z");
}

</style>
