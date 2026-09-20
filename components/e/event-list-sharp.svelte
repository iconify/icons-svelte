<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr_uhabtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:event-list-sharp" {...props}></Icon>
<style>
:global(.pr_uhabtu) {
  fill: currentColor;
  d: path("M14.616 20v-6.384H21V20zM3 17.308v-1h8.23v1zm11.616-6.924V4H21v6.385zM3 7.692v-1h8.23v1z");
}

</style>
