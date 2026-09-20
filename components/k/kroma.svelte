<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="i-a52ob3n"><path class="ivq7x3b_d"/><path class="m7uhdgbjl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:kroma" {...props}></Icon>
<style>
:global(.i-a52ob3n) {
  fill: var(--svg-color--7ae03a, #7ae03a);
}

:global(.ivq7x3b_d) {
  d: path("m12 3.375l-9 5.75L7.5 12L12 9.125L16.5 12L21 9.125z");
}

:global(.m7uhdgbjl) {
  d: path("m21 9.125l-9 5.75l-9-5.75v5.75l9 5.75l9-5.75z");
}

</style>
