<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi3dvnf7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:horizontal-rule-outline" {...props}></Icon>
<style>
:global(.hi3dvnf7f) {
  fill: currentColor;
  d: path("M4 13v-2h16v2z");
}

</style>
