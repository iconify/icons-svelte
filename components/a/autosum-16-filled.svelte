<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hw6wj6bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:autosum-16-filled" {...props}></Icon>
<style>
:global(.hw6wj6bcu) {
  fill: currentColor;
  d: path("M2.06 1.956a.75.75 0 0 1 .69-.456h9.5a.75.75 0 0 1 0 1.5H4.51l3.915 4.08a.75.75 0 0 1 .014 1.023L4.445 12.5h7.805a.75.75 0 0 1 0 1.5h-9.5a.75.75 0 0 1-.555-1.254l4.663-5.133l-4.65-4.844a.75.75 0 0 1-.148-.813");
}

</style>
