<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="p_lqh2b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:presence-blocked-10-regular" {...props}></Icon>
<style>
:global(.p_lqh2b0i) {
  fill: currentColor;
  d: path("M10 5A5 5 0 1 0 0 5a5 5 0 0 0 10 0M9 5a4 4 0 0 1-6.453 3.16L8.16 2.547C8.686 3.224 9 4.076 9 5M7.453 1.84L1.84 7.453A4 4 0 0 1 7.453 1.84");
}

</style>
