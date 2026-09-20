<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lq1ub8bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:align-justify-center-outline-sharp" {...props}></Icon>
<style>
:global(.lq1ub8bof) {
  fill: currentColor;
  d: path("M11.5 21V3h1v18zm3.23-4.5v-9h2v9zm-7.46 0v-9h2v9z");
}

</style>
