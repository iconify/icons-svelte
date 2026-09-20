<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfj_hbcxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:looks-one-sharp" {...props}></Icon>
<style>
:global(.sfj_hbcxi) {
  fill: currentColor;
  d: path("M12 17h2V7h-4v2h2zm9 4H3V3h18z");
}

</style>
