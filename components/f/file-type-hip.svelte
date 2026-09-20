<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rlebhdbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-hip" {...props}></Icon>
<style>
:global(.rlebhdbum) {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M22.37 22.14V9.63H9.86L2.24 2h27.75v27.76zm-1.53.01H9.85v-11L2 19v11h11z");
}

</style>
