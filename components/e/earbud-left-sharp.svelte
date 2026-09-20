<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvmpo9u_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:earbud-left-sharp" {...props}></Icon>
<style>
:global(.xvmpo9u_d) {
  fill: currentColor;
  d: path("M6.789 21v-9.327H4V5h7.558v16zm7.519-7.327V3h.73q2.116 0 3.539 1.577T20 8.327t-1.423 3.76t-3.539 1.586z");
}

</style>
