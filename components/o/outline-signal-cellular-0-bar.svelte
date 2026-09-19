<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqaqhdbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-signal-cellular-0-bar" {...props}></Icon>
<style>
:global(.nqaqhdbvw) {
  fill: currentColor;
  d: path("M2 22h20V2zm18-2H6.83L20 6.83z");
}

</style>
