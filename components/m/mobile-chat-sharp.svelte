<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="koxn03bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mobile-chat-sharp" {...props}></Icon>
<style>
:global(.koxn03bip) {
  fill: currentColor;
  d: path("M5 23V1h14v7h-8v13h2.825l2-2H19v4zm8-4v-9h9v7h-7zm-.288-13.288Q13 5.425 13 5t-.288-.712T12 4t-.712.288T11 5t.288.713T12 6t.713-.288");
}

</style>
