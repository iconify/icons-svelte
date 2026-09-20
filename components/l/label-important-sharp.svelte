<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq-1kubxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:label-important-sharp" {...props}></Icon>
<style>
:global(.dq-1kubxi) {
  fill: currentColor;
  d: path("m2 20l6-8l-6-8h14l6 8l-6 8z");
}

</style>
