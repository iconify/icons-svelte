<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nqlxk4byx"/><path class="gxoky2bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-horizonta-spacing-bold" {...props}></Icon>
<style>
:global(.gxoky2bds) {
  fill: currentColor;
  d: path("M12 4c-1.886 0-2.828 0-3.414.586S8 6.114 8 8v8c0 1.886 0 2.828.586 3.414S10.114 20 12 20s2.828 0 3.414-.586S16 17.886 16 16V8c0-1.886 0-2.828-.586-3.414S13.886 4 12 4");
}

:global(.nqlxk4byx) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 1.25a.75.75 0 0 1 .75.75v20a.75.75 0 0 1-1.5 0V2A.75.75 0 0 1 3 1.25m18 0a.75.75 0 0 1 .75.75v20a.75.75 0 0 1-1.5 0V2a.75.75 0 0 1 .75-.75");
}

</style>
