<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl-hnubfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:more-horizontal" {...props}></Icon>
<style>
:global(.cl-hnubfx) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 12q0-1.75 1.75-1.75T6.5 12t-1.75 1.75T3 12m9-1.75q-1.75 0-1.75 1.75T12 13.75T13.75 12T12 10.25M17.5 12q0-1.75 1.75-1.75T21 12t-1.75 1.75T17.5 12");
}

</style>
