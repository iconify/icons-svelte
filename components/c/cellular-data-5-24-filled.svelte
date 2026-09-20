<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6uyl8brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:cellular-data-5-24-filled" {...props}></Icon>
<style>
:global(.p6uyl8brr) {
  fill: currentColor;
  d: path("M4 17c.552 0 1 .44 1 .984v1.032A.99.99 0 0 1 4 20c-.552 0-1-.44-1-.984v-1.032A.99.99 0 0 1 4 17");
}

</style>
