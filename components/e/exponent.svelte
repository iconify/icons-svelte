<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":240};
const content = `<path class="hyr9zlbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:exponent" {...props}></Icon>
<style>
:global(.hyr9zlbtw) {
  d: path("M94.104-.001L0 217.125l42.193 22.519L128 55.703l85.57 183.941L256 217.125L161.896-.001H94.104z");
  fill: var(--svg-color--023c69, #023C69);
}

</style>
