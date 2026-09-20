<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lbk6cu_lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-volt" {...props}></Icon>
<style>
:global(.lbk6cu_lh) {
  fill: var(--svg-color--gray, gray);
  d: path("M12.068 2h6.866l-2.73 8.421l7.322-1.331L13.115 30l3.037-14.505L8.474 17z");
}

</style>
