<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xji8wacnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:align-self-stretch-sharp" {...props}></Icon>
<style>
:global(.xji8wacnw) {
  fill: currentColor;
  d: path("M3 4V3h18v1zm0 17v-1h18v1zm8-4.5V7h2v9.5z");
}

</style>
