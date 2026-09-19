<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cozo54cho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-group-work" {...props}></Icon>
<style>
:global(.cozo54cho) {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2M8 17.5a2.5 2.5 0 0 1 0-5a2.5 2.5 0 0 1 0 5M9.5 8a2.5 2.5 0 0 1 5 0a2.5 2.5 0 0 1-5 0m6.5 9.5a2.5 2.5 0 0 1 0-5a2.5 2.5 0 0 1 0 5");
}

</style>
