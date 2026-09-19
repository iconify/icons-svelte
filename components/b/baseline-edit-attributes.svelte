<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqazrwkcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-edit-attributes" {...props}></Icon>
<style>
:global(.iqazrwkcv) {
  fill: currentColor;
  d: path("M17.63 7H6.37C3.96 7 2 9.24 2 12s1.96 5 4.37 5h11.26c2.41 0 4.37-2.24 4.37-5s-1.96-5-4.37-5M7.24 14.46l-2.57-2.57l.7-.7l1.87 1.87l3.52-3.52l.7.7z");
}

</style>
