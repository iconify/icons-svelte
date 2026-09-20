<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrllpkq0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mobile-2-sharp" {...props}></Icon>
<style>
:global(.vrllpkq0l) {
  fill: currentColor;
  d: path("M12.713 19.713Q13 19.425 13 19t-.288-.712T12 18t-.712.288T11 19t.288.713T12 20t.713-.288M5 23V1h14v5.1h1v4.8h-1V23z");
}

</style>
