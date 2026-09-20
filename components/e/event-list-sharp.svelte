<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou_wv0b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:event-list-sharp" {...props}></Icon>
<style>
:global(.ou_wv0b-c) {
  fill: currentColor;
  d: path("M14 21v-8h8v8zM2 18v-2h9v2zm12-7V3h8v8zM2 8V6h9v2z");
}

</style>
