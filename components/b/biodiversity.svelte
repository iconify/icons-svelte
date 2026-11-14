<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar8-m0bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:biodiversity" {...props}></Icon>
<style>
:global(.ar8-m0bii) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12");
}

</style>
