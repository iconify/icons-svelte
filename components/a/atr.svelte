<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oiinevb8g"/><path class="hlloqqbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:atr" {...props}></Icon>
<style>
:global(.hlloqqbhf) {
  d: path("M18.75 10.2a2.25 2.25 0 1 0 0-4.5a2.25 2.25 0 0 0 0 4.5");
}

:global(.oiinevb8g) {
  fill-rule: evenodd;
  d: path("M15.6 12.066V12a6.3 6.3 0 1 0-6.3 6.3h6.3z");
}

</style>
