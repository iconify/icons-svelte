<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="xjtbevbpj"/><path class="ge6ieb12h"/><path class="jixhx7bvb"/><path class="ys3n3ybcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-flag-united-arab-emirates" {...props}></Icon>
<style>
:global(.ge6ieb12h) {
  fill: var(--svg-color--eee, #eee);
  d: path("M9 14h27v8H9z");
}

:global(.jixhx7bvb) {
  fill: var(--svg-color--141414, #141414);
  d: path("M9 31h23a4 4 0 0 0 4-4v-5H9z");
}

:global(.xjtbevbpj) {
  fill: var(--svg-color--068241, #068241);
  d: path("M32 5H9v9h27V9a4 4 0 0 0-4-4");
}

:global(.ys3n3ybcv) {
  fill: var(--svg-color--ec2028, #ec2028);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h5V5z");
}

</style>
