<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2bn0mbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:fade-in" {...props}></Icon>
<style>
:global(.e2bn0mbzj) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.625 2.25h-9.25q-2.123 0-3.624 1.501T2.25 7.375v9.25q0 2.123 1.501 3.624t3.624 1.501h9.25q2.123 0 3.624-1.501t1.501-3.624v-9.25q0-2.123-1.501-3.624T16.625 2.25m-6.504 16q-1.504 0-2.079-1.39t.489-2.451l5.878-5.878q1.062-1.064 2.451-.489t1.39 2.079V16q0 2.25-2.25 2.25z");
}

</style>
