<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9kk8xt_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-bungalow" {...props}></Icon>
<style>
:global(.l9kk8xt_a) {
  fill: currentColor;
  d: path("M12 3L4.2 15.5l1.7 1.06L7 14.8V21h4v-5h2v5h4v-6.21l1.1 1.77l1.7-1.06zm1 11h-2v-2h2z");
}

</style>
