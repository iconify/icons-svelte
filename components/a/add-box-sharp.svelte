<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9xbjnbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:add-box-sharp" {...props}></Icon>
<style>
:global(.d9xbjnbtu) {
  fill: currentColor;
  d: path("M11 17h2v-4h4v-2h-4V7h-2v4H7v2h4zm-8 4V3h18v18z");
}

</style>
