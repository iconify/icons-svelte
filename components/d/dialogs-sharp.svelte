<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf49pknzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:dialogs-sharp" {...props}></Icon>
<style>
:global(.jf49pknzu) {
  fill: currentColor;
  d: path("M9 15h6V9H9zm-5 5V4h16v16z");
}

</style>
