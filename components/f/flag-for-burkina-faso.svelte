<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="pas0f6bax"/><path class="ahv46fxbf"/><path class="xk-1frtdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:flag-for-burkina-faso" {...props}></Icon>
<style>
:global(.ahv46fxbf) {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M0 21c0-6.075 3.373-11 10-11h44c6.627 0 10 4.925 10 11v11H0z");
}

:global(.pas0f6bax) {
  fill: var(--svg-color--128807, #128807);
  d: path("M54 54H10C3.373 54 0 49.075 0 43V32h64v11c0 6.075-3.373 11-10 11");
}

:global(.xk-1frtdm) {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("m41.621 29.07l-7.421.01l-2.3-7.506l-2.285 7.506l-7.425-.01l6.01 4.57l-2.327 7.46l6.04-4.637l6.04 4.637l-2.338-7.46z");
}

</style>
