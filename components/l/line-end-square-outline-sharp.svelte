<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d33znabhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:line-end-square-outline-sharp" {...props}></Icon>
<style>
:global(.d33znabhl) {
  fill: currentColor;
  d: path("M13.577 14.923h5.846V9.077h-5.846zm-1 1V12.5h-9.5v-1h9.5V8.077h7.846v7.846zM16.5 12");
}

</style>
