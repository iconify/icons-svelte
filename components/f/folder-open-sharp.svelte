<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyjewcbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:folder-open-sharp" {...props}></Icon>
<style>
:global(.wyjewcbbi) {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v2H4v10l2.4-8h17.1l-3 10z");
}

</style>
