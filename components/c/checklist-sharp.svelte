<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvis35quz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:checklist-sharp" {...props}></Icon>
<style>
:global(.rvis35quz) {
  fill: currentColor;
  d: path("M5.839 17.904L3 15.066l.689-.689l2.125 2.125l4.25-4.25l.688.714zm0-7.231L3 7.835l.689-.689l2.125 2.125l4.25-4.25l.688.714zm7.18 5.442v-1h8v1zm0-7.23v-1h8v1z");
}

</style>
