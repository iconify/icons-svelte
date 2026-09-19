<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1qzedbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-h-plus-mobiledata" {...props}></Icon>
<style>
:global(.f1qzedbqz) {
  fill: currentColor;
  d: path("M12 11H6V7H4v10h2v-4h6v4h2V7h-2zm10 0h-2V9h-2v2h-2v2h2v2h2v-2h2z");
}

</style>
