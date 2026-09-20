<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyyfqbyde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:markunread-mailbox-sharp" {...props}></Icon>
<style>
:global(.oyyfqbyde) {
  fill: currentColor;
  d: path("M2 22V8h4V2h8v4H8v8h2V8h12v14z");
}

</style>
