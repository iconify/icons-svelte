<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="cl66i7bqg"/><path class="c903nt__c"/><path class="tawopabjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-slash-bold-duotone" {...props}></Icon>
<style>
:global(.c903nt__c) {
  fill: currentColor;
  d: path("M19.4697 19.4698C19.7626 19.1769 20.2373 19.1769 20.5302 19.4698L22.5302 21.4698C22.8231 21.7627 22.8231 22.2374 22.5302 22.5303C22.2373 22.8232 21.7626 22.8231 21.4697 22.5303L19.4697 20.5303C19.1768 20.2374 19.1768 19.7627 19.4697 19.4698Z");
}

:global(.cl66i7bqg) {
  cx: 11.5px;
  cy: 11.5px;
  r: 9.5px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.tawopabjo) {
  fill: currentColor;
  d: path("M12.7372 9.20121C13.03 8.90857 13.5049 8.90879 13.7978 9.20121C14.0907 9.4941 14.0907 9.96984 13.7978 10.2627L10.2626 13.7979C9.96976 14.0908 9.49499 14.0907 9.20209 13.7979C8.9092 13.505 8.9092 13.0302 9.20209 12.7373L12.7372 9.20121Z");
}

</style>
