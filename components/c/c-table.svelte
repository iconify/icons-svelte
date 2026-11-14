<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyow673uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:c-table" {...props}></Icon>
<style>
:global(.lyow673uq) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.75h12q2.25 0 2.25 2.25T18 7.25H7.75v9.5H18q2.25 0 2.25 2.25T18 21.25H6q-2.25 0-2.25-2.25T6 16.75h.25v-9.5H6Q3.75 7.25 3.75 5T6 2.75");
}

</style>
