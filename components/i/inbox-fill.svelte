<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j52apjbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:inbox-fill" {...props}></Icon>
<style>
:global(.j52apjbxk) {
  fill: currentColor;
  d: path("M2 6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm18 0a1 1 0 0 0-1-1H5a.997.997 0 0 0-1 1v6h2c1.039 0 1.992.578 2.707 1.293l1 1c.313.312.825.707 1.293.707h2c.468 0 .98-.395 1.293-.707l1-1C16.008 12.578 16.961 12 18 12h2Z");
}

</style>
