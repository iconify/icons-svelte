<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opjb4nsqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:picture-in-picture-medium" {...props}></Icon>
<style>
:global(.opjb4nsqm) {
  fill: currentColor;
  d: path("M3 19v-1h16.385q.23 0 .307-.192q.077-.193.077-.424V5H21v12.385q0 .69-.462 1.153T19.385 19zm4.923-3.384V7.923h9.693v7.693z");
}

</style>
