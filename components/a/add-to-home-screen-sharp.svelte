<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5lhvc84n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:add-to-home-screen-sharp" {...props}></Icon>
<style>
:global(.l5lhvc84n) {
  fill: currentColor;
  d: path("m9.9 15.5l3.1-3.1V15h2V9H9v2h2.6l-3.1 3.1zM5 23V1h14v5.1h1v4.8h-1V23z");
}

</style>
