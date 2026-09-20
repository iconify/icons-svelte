<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkq9-bbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-expand-all-24-regular" {...props}></Icon>
<style>
:global(.fkq9-bbtj) {
  fill: currentColor;
  d: path("M2 4.75A.75.75 0 0 1 2.75 4h18.5a.75.75 0 0 1 0 1.5H2.75A.75.75 0 0 1 2 4.75m10 4a.75.75 0 0 1 .75-.75h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1-.75-.75M7.28 19.78a.75.75 0 0 1-1.06 0l-3-3a.75.75 0 1 1 1.06-1.06L6 17.44V8.75a.75.75 0 0 1 1.5 0v8.69l1.72-1.72a.75.75 0 1 1 1.06 1.06z");
}

</style>
