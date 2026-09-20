<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt4ktwuyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:helicopter" {...props}></Icon>
<style>
:global(.zt4ktwuyu) {
  fill: currentColor;
  d: path("M9 13V7Q6.5 7 4.75 8.75T3 13zm4 9H3v-2h10zm2-3H3q-.825 0-1.412-.587T1 17v-4q0-3.35 2.325-5.675T9 5h6v5h5l1-2h2v7l-8 .8zm4-15H3V2h16z");
}

</style>
