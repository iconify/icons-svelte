<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4uai7b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:chess-rook-sharp" {...props}></Icon>
<style>
:global(.u4uai7b_n) {
  fill: currentColor;
  d: path("M5 21v-4.192q1.929-1.568 2.848-3.295t1.479-3.84H6.866V3h3.788v2.827h2.712V3h3.788v6.673h-2.487q.58 2.114 1.48 3.84T19 16.809V21z");
}

</style>
