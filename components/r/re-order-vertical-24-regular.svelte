<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao1ibroqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:re-order-vertical-24-regular" {...props}></Icon>
<style>
:global(.ao1ibroqf) {
  fill: currentColor;
  d: path("M13.25 21.25V2.75a.75.75 0 0 1 1.493-.102l.007.102v18.5a.75.75 0 0 1-1.493.102zm-4 0V2.75a.75.75 0 0 1 1.493-.102l.007.102v18.5a.75.75 0 0 1-1.493.102z");
}

</style>
