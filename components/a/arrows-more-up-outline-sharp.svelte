<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkuxsmbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrows-more-up-outline-sharp" {...props}></Icon>
<style>
:global(.mkuxsmbtn) {
  fill: currentColor;
  d: path("M13 18V9H4V8h10v10zm4-3.98v-9H8v-1h10v10z");
}

</style>
