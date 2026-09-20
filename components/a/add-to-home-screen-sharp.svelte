<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypcj-ides"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:add-to-home-screen-sharp" {...props}></Icon>
<style>
:global(.ypcj-ides) {
  fill: currentColor;
  d: path("m9.689 15l3.811-3.811v3.215h1V9.48H9.577v1h3.235L8.98 14.292zM6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
