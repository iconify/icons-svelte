<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8zae1wfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:eject-rounded" {...props}></Icon>
<style>
:global(.l8zae1wfd) {
  fill: currentColor;
  d: path("M6 17h12q.425 0 .713.288T19 18t-.288.713T18 19H6q-.425 0-.712-.288T5 18t.288-.712T6 17m.375-3.55l4.8-7.2q.15-.225.363-.338T12 5.8t.463.113t.362.337l4.8 7.2q.35.5.05 1.025t-.9.525h-9.55q-.6 0-.9-.525t.05-1.025");
}

</style>
