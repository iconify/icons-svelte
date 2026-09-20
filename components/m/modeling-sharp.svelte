<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xk-8csbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:modeling-sharp" {...props}></Icon>
<style>
:global(.xk-8csbgj) {
  fill: currentColor;
  d: path("m17.866 19.289l-3.347-3.308l3.346-3.308l.689.708l-2.113 2.1H21v1h-4.56l2.114 2.1zM3 19v-6.038h9.173V19zm3.135-7.692l-.689-.708L7.56 8.5H3v-1h4.56L5.446 5.4l.688-.688L9.481 8zm5.692-.27V5H21v6.039z");
}

</style>
