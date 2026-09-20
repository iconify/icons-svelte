<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_f9rqbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:h-plus-mobiledata-badge-sharp" {...props}></Icon>
<style>
:global(.f_f9rqbrk) {
  fill: currentColor;
  d: path("M4.5 17h2v-4h4v4h2V7h-2v4h-4V7h-2zm11-2h2v-2h2v-2h-2V9h-2v2h-2v2h2zM1 21V3h22v18z");
}

</style>
