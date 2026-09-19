<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wztibb18j"/><path class="qvbeni15f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-gpp-maybe" {...props}></Icon>
<style>
:global(.qvbeni15f) {
  fill: currentColor;
  d: path("M11 14h2v2h-2zm0-7h2v5h-2z");
}

:global(.wztibb18j) {
  fill: currentColor;
  d: path("M12 2L4 5v6.09c0 5.05 3.41 9.76 8 10.91c4.59-1.15 8-5.86 8-10.91V5zm6 9.09c0 4-2.55 7.7-6 8.83c-3.45-1.13-6-4.82-6-8.83v-4.7l6-2.25l6 2.25z");
}

</style>
