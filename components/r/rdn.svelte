<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsk2v76ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:rdn" {...props}></Icon>
<style>
:global(.vsk2v76ms) {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.093 13C14.13 7.28 8.713 3.95 6 3h7.623c3.613 2.654 4.422 7.773 4.375 10zM8.5 10v11l5-2.785z");
}

</style>
