<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-q6l7u7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:ong" {...props}></Icon>
<style>
:global(.e-q6l7u7i) {
  fill: var(--svg-color--329afa, #329afa);
  d: path("M3 12.816V3l14.625 15.469a10.3 10.3 0 0 1-4.399 2.402c-.995.225-3.965.376-6.682-1.575C3.827 17.355 3 14.25 3 12.82zm18-1.632V21L6.375 5.531a10.3 10.3 0 0 1 4.399-2.402c.995-.225 3.965-.377 6.682 1.575C20.173 6.645 21 9.75 21 11.18z");
}

</style>
