<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc2pw_b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:looks-0-sharp" {...props}></Icon>
<style>
:global(.uc2pw_b0v) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm6-4h6V7H9zm2-2V9h2v6z");
}

</style>
