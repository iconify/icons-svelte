<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7ndhubee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:folder-code-sharp" {...props}></Icon>
<style>
:global(.b7ndhubee) {
  fill: currentColor;
  d: path("M14.6 22.6L11 19l3.6-3.6l1.4 1.425L13.825 19L16 21.175zm4.8 0L18 21.175L20.175 19L18 16.825l1.4-1.425L23 19zM2 20V4h8l2 2h10v7h-7q-2.5 0-4.25 1.75T9 19v1z");
}

</style>
