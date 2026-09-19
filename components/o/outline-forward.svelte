<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqf2hfhaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-forward" {...props}></Icon>
<style>
:global(.dqf2hfhaf) {
  fill: currentColor;
  d: path("M14 8.83L17.17 12L14 15.17V14H6v-4h8zM12 4v4H4v8h8v4l8-8z");
}

</style>
