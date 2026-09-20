<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kelc__9cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:panorama-outline-sharp" {...props}></Icon>
<style>
:global(.kelc__9cw) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h16V6H4zm3.5-2h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115zM4 18V6z");
}

</style>
