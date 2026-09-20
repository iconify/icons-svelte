<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkrj1mbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:change-history-outline" {...props}></Icon>
<style>
:global(.bkrj1mbdq) {
  fill: currentColor;
  d: path("M3.808 19L12 5.885L20.192 19zM5.6 18h12.8L12 7.75zm6.4-5.125");
}

</style>
