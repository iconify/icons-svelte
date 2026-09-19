<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="df-f1m7nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-takeout-dining" {...props}></Icon>
<style>
:global(.df-f1m7nt) {
  fill: currentColor;
  d: path("m7.79 18l-.51-7h9.46l-.51 7zM9.83 5h4.33l2.8 2.73L16.87 9H7.12l-.09-1.27zM22 7.46l-1.41-1.41L19 7.63l.03-.56L14.98 3H9.02L4.97 7.07l.03.5l-1.59-1.56L2 7.44l3.23 3.11l.7 9.45h12.14l.7-9.44z");
}

</style>
