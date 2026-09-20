<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="m50ubiwhr"><path class="ysi8z112o"/><path class="r0aq5bbad"/><path class="nk4dd4b0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:clv" {...props}></Icon>
<style>
:global(.m50ubiwhr) {
  fill: var(--svg-color--50c07c, #50c07c);
}

:global(.nk4dd4b0d) {
  d: path("M21 16.5a4.5 4.5 0 1 0-9 0a4.5 4.5 0 0 0 9 0");
}

:global(.r0aq5bbad) {
  d: path("M12 16.5a4.5 4.5 0 1 0-9 0a4.5 4.5 0 0 0 9 0m9-9a4.5 4.5 0 1 0-9 0a4.5 4.5 0 0 0 9 0");
}

:global(.ysi8z112o) {
  d: path("M12 7.5a4.5 4.5 0 1 0-9 0a4.5 4.5 0 0 0 9 0");
}

</style>
