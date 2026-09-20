<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_4vmdfre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:input-outline-sharp" {...props}></Icon>
<style>
:global(.f_4vmdfre) {
  fill: currentColor;
  d: path("M2 20v-5h2v3h16V6H4v3H2V4h20v16zm9.5-3.5l-1.4-1.45L12.175 13H2v-2h10.175L10.1 8.95l1.4-1.45L16 12z");
}

</style>
