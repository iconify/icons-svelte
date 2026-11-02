<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8j4vrn4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:component-instance-fill-sharp" {...props}></Icon>
<style>
:global(.m8j4vrn4r) {
  fill: currentColor;
  d: path("M22.707 11.293a1 1 0 0 1 0 1.414l-10 10a1 1 0 0 1-1.414 0l-10-10a1 1 0 0 1 0-1.414l10-10a1 1 0 0 1 1.414 0Z");
}

</style>
