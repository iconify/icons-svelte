<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="ysr_j2ijm"/><path class="htc3j7bzm"/><path class="e_q28_yfr"/><path class="qtiz3vbvv"/><path class="m4aq2w5tw"/><path class="asvfy0bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-south-africa" {...props}></Icon>
<style>
:global(.asvfy0bao) {
  fill: var(--svg-color--eee, #eee);
  d: path("M6.5 5H4q-.233.001-.459.028L18.5 15.5H36v-2H19zM3.541 30.972q.226.027.459.028h2.5L19 22.5h17v-2H18.5z");
}

:global(.e_q28_yfr) {
  fill: var(--svg-color--141414, #141414);
  d: path("M0 11v14l10.5-7z");
}

:global(.htc3j7bzm) {
  fill: var(--svg-color--002395, #002395);
  d: path("M6.5 31H32a4 4 0 0 0 4-4v-4.5H19z");
}

:global(.m4aq2w5tw) {
  fill: var(--svg-color--007a4d, #007a4d);
  d: path("M3.541 5.028A4 4 0 0 0 0 9l13.5 9L0 27a4 4 0 0 0 3.541 3.972L18.5 20.5H36v-5H18.5z");
}

:global(.qtiz3vbvv) {
  fill: var(--svg-color--ffb611, #ffb611);
  d: path("M0 9v2l10.5 7L0 25v2l13.5-9z");
}

:global(.ysr_j2ijm) {
  fill: var(--svg-color--de3830, #de3830);
  d: path("M32 5H6.5L19 13.5h17V9a4 4 0 0 0-4-4");
}

</style>
