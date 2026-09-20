<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3wcrjryr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:files-outline-sharp" {...props}></Icon>
<style>
:global(.f3wcrjryr) {
  fill: currentColor;
  d: path("M2 20V6h8l2-2h10v16zm3.825-7H11V7.825zM4 12l4-4H4zm0 3v3h16V6h-7v9zm7-4");
}

</style>
