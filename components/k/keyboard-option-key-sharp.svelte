<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6r49jtdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:keyboard-option-key-sharp" {...props}></Icon>
<style>
:global(.z6r49jtdc) {
  fill: currentColor;
  d: path("M14.775 19L7.85 7H3V5h6l6.925 12H21v2zM15 7V5h6v2z");
}

</style>
