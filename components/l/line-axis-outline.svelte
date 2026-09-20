<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl5ngg-qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:line-axis-outline" {...props}></Icon>
<style>
:global(.kl5ngg-qn) {
  fill: currentColor;
  d: path("m3.5 18.23l-.73-.73l6.807-6.808l4 4l2.367-2.727l-6.33-5.848L3.5 12.231l-.73-.731l6.807-6.808l7.062 6.506l3.923-4.506l.707.67l-3.892 4.507l3.892 3.593l-.73.73l-3.85-3.55l-3.073 3.55l-4.039-4.038z");
}

</style>
