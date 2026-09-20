<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko9t8y8rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:border-all" {...props}></Icon>
<style>
:global(.ko9t8y8rs) {
  fill: currentColor;
  d: path("M13 21v-8h8v8zm0-10V3h8v8zM3 11V3h8v8zm0 10v-8h8v8z");
}

</style>
