<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmksqvbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:files-outline" {...props}></Icon>
<style>
:global(.wmksqvbdt) {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V8q0-.825.588-1.412T4 6h6l2-2h8q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm1.825-7H11V7.825zM4 12l4-4H4zm0 3v3h16V6h-7v7q0 .825-.587 1.413T11 15zm7-4");
}

</style>
