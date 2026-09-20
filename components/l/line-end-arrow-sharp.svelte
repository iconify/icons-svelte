<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ueoq-jg_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:line-end-arrow-sharp" {...props}></Icon>
<style>
:global(.ueoq-jg_k) {
  fill: currentColor;
  d: path("M12.192 16.827V12.5H3.077v-1h9.115V7.173L19.788 12z");
}

</style>
