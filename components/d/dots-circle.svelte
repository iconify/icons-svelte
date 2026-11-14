<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iho5djb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:dots-circle" {...props}></Icon>
<style>
:global(.iho5djb3h) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.5q-1.5 0-1.5 1.5T12 5.5T13.5 4T12 2.5M4.75 6.25q0-1.5 1.5-1.5q.621 0 1.061.439q.439.44.439 1.061t-.439 1.061q-.44.439-1.061.439q-1.5 0-1.5-1.5m11.5 0q0-1.5 1.5-1.5t1.5 1.5t-1.5 1.5t-1.5-1.5M4 10.5q-1.5 0-1.5 1.5T4 13.5T5.5 12T4 10.5m16 0q-1.5 0-1.5 1.5t1.5 1.5t1.5-1.5t-1.5-1.5M4.75 17.75q0-1.5 1.5-1.5q.621 0 1.061.439q.439.44.439 1.061t-.439 1.061q-.44.439-1.061.439q-1.5 0-1.5-1.5m11.5 0q0-1.5 1.5-1.5t1.5 1.5t-1.5 1.5t-1.5-1.5M12 18.5q-1.5 0-1.5 1.5t1.5 1.5t1.5-1.5t-1.5-1.5");
}

</style>
