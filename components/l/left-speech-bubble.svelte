<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="zcizd98ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:left-speech-bubble" {...props}></Icon>
<style>
:global(.zcizd98ek) {
  fill: var(--svg-color--8ccaf7, #8ccaf7);
  d: path("M18 1c9.941 0 18 6.268 18 14c0 4.368-2.574 8.268-6.604 10.835C29.92 28.144 31.141 31.569 34 35c-5.758-.96-9.44-3.761-11.716-6.416A23 23 0 0 1 18 29C8.059 29 0 22.732 0 15S8.059 1 18 1");
}

</style>
