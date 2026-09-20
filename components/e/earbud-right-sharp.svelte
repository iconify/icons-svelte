<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7k103kav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:earbud-right-sharp" {...props}></Icon>
<style>
:global(.z7k103kav) {
  fill: currentColor;
  d: path("M12 22V4h9v8h-3v10zm-3-8q-2.5 0-4.25-1.75T3 8t1.75-4.25T9 2h1v12z");
}

</style>
