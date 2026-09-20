<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="obz-2rb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:communication-16-regular" {...props}></Icon>
<style>
:global(.obz-2rb7x) {
  fill: currentColor;
  d: path("M8 3a6 6 0 0 0-4.246 10.239a.5.5 0 1 1-.708.706a7 7 0 1 1 9.908 0a.5.5 0 1 1-.708-.706A6 6 0 0 0 8 3m0 2.5a3.5 3.5 0 0 0-2.475 5.975a.5.5 0 1 1-.707.707a4.5 4.5 0 1 1 6.364 0a.5.5 0 0 1-.707-.707A3.5 3.5 0 0 0 8 5.5M8 7a2 2 0 1 0 0 4a2 2 0 0 0 0-4M7 9a1 1 0 1 1 2 0a1 1 0 0 1-2 0");
}

</style>
