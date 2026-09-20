<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qolazk7ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:new-label-outline" {...props}></Icon>
<style>
:global(.qolazk7ot) {
  fill: currentColor;
  d: path("M12.27 19v-1h2.557q.154 0 .279-.058t.221-.173L19.75 12l-4.423-5.77q-.096-.114-.221-.172T14.827 6H4.616q-.27 0-.443.173T4 6.616v4H3v-4.01q0-.662.475-1.134Q3.949 5 4.615 5h10.212q.384 0 .727.167t.565.46L21 12l-4.88 6.373q-.223.294-.566.46t-.727.167zm-6.385 1v-3h-3v-1h3v-3h1v3h3v1h-3v3z");
}

</style>
