<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnwqly4dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:replace-video-sharp" {...props}></Icon>
<style>
:global(.hnwqly4dt) {
  fill: currentColor;
  d: path("M4.327 8.77q.739-2.572 2.864-4.171T12 3q2.223 0 4.099 1.144T19 7.234V4h1v4.77h-4.77v-1h2.862q-.84-1.726-2.49-2.748T12 4Q9.725 4 7.907 5.306t-2.52 3.463zM6.385 21V11h10v4.5L19 12.885v6.23L16.384 16.5V21z");
}

</style>
