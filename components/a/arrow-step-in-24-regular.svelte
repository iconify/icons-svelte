<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nauzctb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-step-in-24-regular" {...props}></Icon>
<style>
:global(.nauzctb2a) {
  fill: currentColor;
  d: path("M12 2a.75.75 0 0 1 .75.75v9.256l3.484-3.3a.75.75 0 1 1 1.032 1.088l-4.75 4.5a.75.75 0 0 1-1.032 0l-4.75-4.5a.75.75 0 0 1 1.032-1.088l3.484 3.3V2.75A.75.75 0 0 1 12 2m0 20a3 3 0 1 0 0-6a3 3 0 0 0 0 6m0-1.5a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3");
}

</style>
