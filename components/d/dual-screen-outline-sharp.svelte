<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru4lk2pcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:dual-screen-outline-sharp" {...props}></Icon>
<style>
:global(.ru4lk2pcr) {
  fill: currentColor;
  d: path("m6 17.6l6 2.4V6.4L6 4zm-2 1.35V2h2l8 3.025V22.95zm8 .05v-2h6V4H6V2h14v17zm-6-1.4V4z");
}

</style>
