<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1-m95bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:h-mobiledata-badge-sharp" {...props}></Icon>
<style>
:global(.o1-m95bxx) {
  fill: currentColor;
  d: path("M8 17h2v-4h4v4h2V7h-2v4h-4V7H8zm-5 4V3h18v18z");
}

</style>
