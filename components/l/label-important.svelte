<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-zpa91pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:label-important" {...props}></Icon>
<style>
:global(.n-zpa91pq) {
  fill: currentColor;
  d: path("m2 20l6-8l-6-8h13q.475 0 .9.213t.7.587L22 12l-5.4 7.2q-.275.375-.7.588T15 20z");
}

</style>
