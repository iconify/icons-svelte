<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkuq_cbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:keyboard-tab" {...props}></Icon>
<style>
:global(.zkuq_cbiq) {
  fill: currentColor;
  d: path("M20 18V6h2v12zm-8 0l-1.425-1.4l3.6-3.6H2v-2h12.175L10.6 7.4L12 6l6 6z");
}

</style>
