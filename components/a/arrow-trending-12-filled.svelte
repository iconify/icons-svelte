<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sjtisebup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-trending-12-filled" {...props}></Icon>
<style>
:global(.sjtisebup) {
  fill: currentColor;
  d: path("M6.25 1.5a.75.75 0 0 0 0 1.5h2.323L5.97 5.91l-.94-.94a.75.75 0 0 0-1.06 0L1.22 7.72a.75.75 0 0 0 1.06 1.06L4.5 6.56l.97.97a.75.75 0 0 0 1.089-.03L9.5 4.213V6.25a.75.75 0 0 0 1.5 0v-4a.75.75 0 0 0-.75-.75z");
}

</style>
