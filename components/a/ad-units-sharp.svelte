<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu8q2zrdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:ad-units-sharp" {...props}></Icon>
<style>
:global(.qu8q2zrdb) {
  fill: currentColor;
  d: path("M8 12h8v-2H8zM5 23V1h14v5.1h1v4.8h-1V23z");
}

</style>
