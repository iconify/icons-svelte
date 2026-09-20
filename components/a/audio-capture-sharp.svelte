<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whdw9jb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:audio-capture-sharp" {...props}></Icon>
<style>
:global(.whdw9jb9f) {
  fill: currentColor;
  d: path("M2 22V12h2v5.125L5.15 16H8v2H6zm14-4v-2h4v-4h2v6zm-5-3V5h2v10zm-4-2V7h2v6zm8-1V8h2v4zM2 8V2h6v2H4v4zm18 0V4h-4V2h6v6z");
}

</style>
