<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="d7qpykbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-fat-up-bold" {...props}></Icon>
<style>
:global(.d7qpykbfe) {
  fill: currentColor;
  d: path("m232.48 111.51l-96-96a12 12 0 0 0-17 0l-96 96A12 12 0 0 0 32 132h36v76a20 20 0 0 0 20 20h80a20 20 0 0 0 20-20v-76h36a12 12 0 0 0 8.48-20.49M176 108a12 12 0 0 0-12 12v84H92v-84a12 12 0 0 0-12-12H61l67-67l67 67Z");
}

</style>
