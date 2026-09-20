<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="ck_zz3bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:flip-vertical-28-filled" {...props}></Icon>
<style>
:global(.ck_zz3bxf) {
  fill: currentColor;
  d: path("M23.543 2.16A1 1 0 0 1 24 3v9a1 1 0 0 1-1 1H3a1 1 0 0 1-.41-1.912l20-9a1 1 0 0 1 .953.072M7.66 11H22V4.547zM24 25.25a.75.75 0 0 1-1.065.68l-20.5-9.5A.75.75 0 0 1 2.75 15h20.5a.75.75 0 0 1 .75.75z");
}

</style>
