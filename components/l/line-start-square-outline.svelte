<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prx_zibmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:line-start-square-outline" {...props}></Icon>
<style>
:global(.prx_zibmv) {
  fill: currentColor;
  d: path("M4 15.5h7v-7H4zm9 2H2v-11h11V11h9v2h-9zM7.5 12");
}

</style>
