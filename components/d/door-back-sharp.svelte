<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3-wyxb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:door-back-sharp" {...props}></Icon>
<style>
:global(.n3-wyxb3m) {
  fill: currentColor;
  d: path("M4 20v-1h2V4h12v15h2v1zm6.309-7.46q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23T9 12t.23.54t.54.23t.539-.23");
}

</style>
