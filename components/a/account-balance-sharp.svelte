<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhbrj6blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:account-balance-sharp" {...props}></Icon>
<style>
:global(.rhbrj6blr) {
  fill: currentColor;
  d: path("M5 17v-7h2v7zm6 0v-7h2v7zm-9 4v-2h20v2zm15-4v-7h2v7zM2 8V6l10-5l10 5v2z");
}

</style>
