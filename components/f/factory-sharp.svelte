<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajl35wbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:factory-sharp" {...props}></Icon>
<style>
:global(.ajl35wbzz) {
  fill: currentColor;
  d: path("M2 22V9.975L9 7v2l5-2v3h8v12zm9-4h2v-4h-2zm-4 0h2v-4H7zm8 0h2v-4h-2zm6.8-9.5h-4.625l.85-6.5H21z");
}

</style>
