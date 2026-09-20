<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjm-_2b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:drafts-sharp" {...props}></Icon>
<style>
:global(.mjm-_2b4a) {
  fill: currentColor;
  d: path("m12 1l10 5.975V21H2V6.975zm0 11.65L19.8 8L12 3.35L4.2 8z");
}

</style>
