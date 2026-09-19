<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zclxvabej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:flag-for-gambia" {...props}></Icon>
<style>
:global(.zclxvabej) {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2M6.175 43a29 29 0 0 1-.734-2h53.117a29 29 0 0 1-.734 2zm-.734-20c.223-.666.464-1.357.734-2h51.649c.271.643.512 1.334.734 2z");
}

</style>
