<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti88hy8pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-text-decrease" {...props}></Icon>
<style>
:global(.ti88hy8pn) {
  fill: currentColor;
  d: path("M.99 19h2.42l1.27-3.58h5.65L11.59 19h2.42L8.75 5h-2.5zm4.42-5.61L7.44 7.6h.12l2.03 5.79zM23 11v2h-8v-2z");
}

</style>
