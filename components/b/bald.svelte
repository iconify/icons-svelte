<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="l1_8d-czw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:bald" {...props}></Icon>
<style>
:global(.l1_8d-czw) {
  fill: var(--svg-color--ffdc5d, #FFDC5D);
  d: path("M34.896 36C30.618 13.677 16.169 2.725 0 1.195V36h34.896z");
}

</style>
