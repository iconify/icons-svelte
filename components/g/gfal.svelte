<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_ea6-ain"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:gfal" {...props}></Icon>
<style>
:global(.q_ea6-ain) {
  fill: var(--svg-color--f113a3, #f113a3);
  d: path("M4.059 16.5v-9L12 3l4.04 2.25l-8.275 4.78v4.781L12 16.765l4.235-2.118V9.861L19.941 7.5v9L12 21z");
}

</style>
