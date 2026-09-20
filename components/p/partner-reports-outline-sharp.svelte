<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzeld7bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:partner-reports-outline-sharp" {...props}></Icon>
<style>
:global(.fzeld7bks) {
  fill: currentColor;
  d: path("M11 13V3h2v10zm-8 8v-5h2v3h14v-3h2v5zm8-4v-2h2v2z");
}

</style>
