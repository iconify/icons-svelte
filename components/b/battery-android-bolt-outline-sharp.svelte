<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwu_2yqxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:battery-android-bolt-outline-sharp" {...props}></Icon>
<style>
:global(.hwu_2yqxo) {
  fill: currentColor;
  d: path("M2 17V7h15.723l-.792 1H3v8h12.998l-.202 1zm1-1V8zm14.867.23l.604-3.384h-2.855l4.069-5.077h.448l-.604 3.385h2.856l-4.07 5.077z");
}

</style>
