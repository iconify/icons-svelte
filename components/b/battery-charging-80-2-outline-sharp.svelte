<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1bobsbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:battery-charging-80-2-outline-sharp" {...props}></Icon>
<style>
:global(.x1bobsbun) {
  fill: currentColor;
  d: path("M2.5 16.5v-9h12.962l-.812 1H12.5v7h2.154l-.177 1zm14.867 0l.604-3.712h-2.933L18.417 7.5h.217l-.604 3.712h2.933L17.585 16.5z");
}

</style>
