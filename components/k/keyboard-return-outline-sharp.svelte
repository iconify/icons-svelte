<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfy0qybbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:keyboard-return-outline-sharp" {...props}></Icon>
<style>
:global(.zfy0qybbd) {
  fill: currentColor;
  d: path("M9.308 17.308L4 12l5.308-5.308l.708.708l-4.1 4.1H19v-4h1v5H5.916l4.1 4.1z");
}

</style>
