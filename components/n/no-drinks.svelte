<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfh09tbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:no-drinks" {...props}></Icon>
<style>
:global(.hfh09tbel) {
  fill: currentColor;
  d: path("M7 20.5v-1h4.5v-6.573l-8.754-8.76l.708-.713l17.092 17.092l-.713.714l-7.333-7.333V19.5H17v1zm7.07-9.242L9.811 7h6.738l1.8-2H7.811l-1-1h12.843v1z");
}

</style>
