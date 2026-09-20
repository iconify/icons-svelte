<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqhgd4nav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:rectangle-rounded" {...props}></Icon>
<style>
:global(.qqhgd4nav) {
  fill: currentColor;
  d: path("M4.616 19q-.667 0-1.141-.475T3 17.386V6.615q0-.666.475-1.14T4.615 5h14.77q.666 0 1.14.475T21 6.615v10.77q0 .666-.475 1.14t-1.14.475z");
}

</style>
