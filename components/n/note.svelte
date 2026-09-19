<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbw0tn9nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:note" {...props}></Icon>
<style>
:global(.cbw0tn9nz) {
  fill: currentColor;
  d: path("m22 10l-6-6H4c-1.1 0-2 .9-2 2v12.01c0 1.1.9 1.99 2 1.99l16-.01c1.1 0 2-.89 2-1.99zm-7-4.5l5.5 5.5H15z");
}

</style>
