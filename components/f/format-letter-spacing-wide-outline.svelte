<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox0qi1els"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:format-letter-spacing-wide-outline" {...props}></Icon>
<style>
:global(.ox0qi1els) {
  fill: currentColor;
  d: path("M4 19V5h1v14zm15 0V5h1v14zM7.773 17l3.673-9.923h1.05L16.227 17H15.15l-1.004-2.839H9.808L8.812 17zm2.362-3.712h3.692l-1.816-5.111h-.038z");
}

</style>
