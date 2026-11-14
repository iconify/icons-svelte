<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdobf4bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:context-menu" {...props}></Icon>
<style>
:global(.zdobf4bga) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 5q0-2.25 2.25-2.25T14.25 5T12 7.25T9.75 5M12 9.75q-2.25 0-2.25 2.25T12 14.25T14.25 12T12 9.75M9.75 19q0-2.25 2.25-2.25T14.25 19T12 21.25T9.75 19");
}

</style>
