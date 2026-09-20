<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8duo8bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:credit-card-sharp" {...props}></Icon>
<style>
:global(.h8duo8bsh) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-7.808h16V8.808H4z");
}

</style>
