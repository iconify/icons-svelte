<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvy53sl2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:diamond" {...props}></Icon>
<style>
:global(.qvy53sl2l) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.386 3.826l5.788 5.788q2.386 2.386 0 4.772l-5.788 5.788q-2.386 2.386-4.772 0l-5.788-5.788Q1.44 12 3.826 9.614l5.788-5.788q2.386-2.386 4.772 0");
}

</style>
