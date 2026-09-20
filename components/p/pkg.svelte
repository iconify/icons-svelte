<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":229};
const content = `<path class="zga_kob9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:pkg" {...props}></Icon>
<style>
:global(.zga_kob9z) {
  d: path("M130.307 0L256 180.877l-124.098 47.816v-24.72l9.772-5.985zm-4.626.004l-9.424 164.25l-.776 13.526l-1.164 20.288l9.756 5.786v24.811l-33.031-12.718l-16.48-6.346C49.841 200.08 25.1 190.555 0 180.89l17.84-25.676l8.912-12.827z");
}

</style>
