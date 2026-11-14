<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjw73ib6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:home-smoke-detector" {...props}></Icon>
<style>
:global(.gjw73ib6b) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 12q-.001-3.832 2.708-6.543q2.71-2.71 6.542-2.71t6.542 2.71Q21.251 8.168 21.25 12q.001 3.832-2.708 6.543q-2.71 2.71-6.542 2.71t-6.542-2.71T2.75 12m6.245-3.005Q7.75 10.24 7.75 12t1.245 3.005T12 16.25t3.005-1.245T16.25 12t-1.245-3.005T12 7.75T8.995 8.995");
}

</style>
