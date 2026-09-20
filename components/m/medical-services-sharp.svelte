<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isvm1dbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:medical-services-sharp" {...props}></Icon>
<style>
:global(.isvm1dbxx) {
  fill: currentColor;
  d: path("M2 22V6h6V2h8v4h6v16zm8-16h4V4h-4zm1 9v3h2v-3h3v-2h-3v-3h-2v3H8v2z");
}

</style>
