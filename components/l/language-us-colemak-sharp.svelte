<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3e4v489a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:language-us-colemak-sharp" {...props}></Icon>
<style>
:global(.p3e4v489a) {
  fill: currentColor;
  d: path("M13.577 15.5H18v-7h-4.423zM5 16.5v-9h5.577v1H6v7h4.577v1zm7.577 0v-9H19v9z");
}

</style>
