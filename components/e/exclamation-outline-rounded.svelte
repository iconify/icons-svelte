<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4qy-jbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:exclamation-outline-rounded" {...props}></Icon>
<style>
:global(.h4qy-jbfj) {
  fill: currentColor;
  d: path("M11.643 13.933q-.143-.143-.143-.356v-7q0-.212.144-.356t.357-.144t.356.144t.143.356v7q0 .213-.144.356t-.357.144t-.356-.144m0 3.846q-.143-.144-.143-.357t.144-.356t.357-.143t.356.144t.143.357t-.144.356t-.357.143t-.356-.144");
}

</style>
