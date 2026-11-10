<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sg305nbyc"/><path class="wp8zslaea"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:joystick-sharp-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.sg305nbyc) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 13C21.552 13 22 13.45 22 14V20C22 20.55 21.552 21 21 21H3C2.448 21 2 20.55 2 20V14C2 13.45 2.448 13 3 13H21Z");
}

:global(.wp8zslaea) {
  d: path("M16 3C18.209 3 20 4.79 20 7C20 9.21 18.209 11 16 11C15.776 11 15.556 10.98 15.341 10.94L14.428 13H12.238L13.514 10.13C12.593 9.4 12 8.27 12 7C12 4.79 13.791 3 16 3Z");
}

</style>
