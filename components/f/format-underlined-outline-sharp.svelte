<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjava7b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:format-underlined-outline-sharp" {...props}></Icon>
<style>
:global(.gjava7b-w) {
  fill: currentColor;
  d: path("M5.692 19.25v-1h12.616v1zm2.95-4.45q-1.217-1.258-1.217-3.415V3.827h1.133v7.592q0 1.631.911 2.583q.912.952 2.531.952t2.53-.952t.912-2.583V3.827h1.133v7.558q0 2.157-1.217 3.415T12 16.058T8.642 14.8");
}

</style>
