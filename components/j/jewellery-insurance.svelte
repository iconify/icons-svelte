<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gl53vvbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:jewellery-insurance" {...props}></Icon>
<style>
:global(.gl53vvbdx) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.509 4.529v-.001l.411-.685q.655-1.093 1.929-1.093h2.302q1.274 0 1.929 1.092l.411.687q.977 1.628-.465 2.864l-1.562 1.339q-.458.393-.917.54q2.135.175 3.696 1.735Q18 12.765 18 15.25t-1.757 4.243T12 21.25t-4.243-1.757Q6 17.735 6 15.25t1.757-4.243q1.561-1.56 3.696-1.735q-.459-.147-.917-.539l-1.562-1.34q-1.442-1.236-.465-2.864");
}

</style>
