<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwsrrqbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:done-all" {...props}></Icon>
<style>
:global(.qwsrrqbhm) {
  fill: currentColor;
  d: path("M6.7 17.308L1.742 12.35l.714-.708l4.25 4.25l.692-.692l.708.708zm5.65 0L7.392 12.35l.708-.713l4.25 4.25l9.2-9.2l.708.713zm-.692-4.958l-.714-.708l4.95-4.95l.714.708z");
}

</style>
