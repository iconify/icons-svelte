<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpyoaugyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:gem-fill-round" {...props}></Icon>
<style>
:global(.tpyoaugyr) {
  fill: currentColor;
  d: path("M14.081 18.182a2.8 2.8 0 0 1-4.162 0l-6.393-7.103a3 3 0 0 1 .109-4.128l1.486-1.487A5 5 0 0 1 8.657 4h6.686c1.326 0 2.598.527 3.536 1.464l1.486 1.487a3 3 0 0 1 .109 4.128ZM8.707 8.293a.999.999 0 1 0-1.414 1.414l2 2a.999.999 0 1 0 1.414-1.414Z");
}

</style>
