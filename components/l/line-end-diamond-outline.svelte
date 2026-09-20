<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4z3iqbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:line-end-diamond-outline" {...props}></Icon>
<style>
:global(.r4z3iqbqb) {
  fill: currentColor;
  d: path("M15 16.175L19.175 12L15 7.825L10.825 12zM15 19l-6-6H2v-2h7l6-6l7 7zm0-7");
}

</style>
