<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgy3h4v9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:phonelink-erase-sharp" {...props}></Icon>
<style>
:global(.lgy3h4v9n) {
  fill: currentColor;
  d: path("M4 23V1h14v6h-2V6H6v12h10v-1h2v6zm10.4-7L13 14.6l2.6-2.6L13 9.4L14.4 8l2.6 2.6L19.6 8L21 9.4L18.4 12l2.6 2.6l-1.4 1.4l-2.6-2.6z");
}

</style>
