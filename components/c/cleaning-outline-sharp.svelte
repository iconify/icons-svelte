<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6vc5-xme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:cleaning-outline-sharp" {...props}></Icon>
<style>
:global(.g6vc5-xme) {
  fill: currentColor;
  d: path("m9 7l1-2V4H9V2h7v2l-1 2h-3V5l-2 2zM8 22v-7.425L12 7h4v15zm2-2h4V9h-.8L10 15.1zm0 0h4z");
}

</style>
