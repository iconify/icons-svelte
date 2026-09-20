<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="eqsxunb5s"/><path class="dhd_xvbxt"/><path class="jkkarl48q"/><path class="p4mxzbu9q"/><path class="ct06jo4ix"/><path class="l3nd-xz_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-central-african-republic" {...props}></Icon>
<style>
:global(.ct06jo4ix) {
  fill: var(--svg-color--d21034, #D21034);
  d: path("M15 5h6v26h-6z");
}

:global(.dhd_xvbxt) {
  fill: var(--svg-color--eee, #EEE);
  d: path("M0 11.5h36V18H0z");
}

:global(.eqsxunb5s) {
  fill: var(--svg-color--003082, #003082);
  d: path("M32 5H4a4 4 0 0 0-4 4v2.5h36V9a4 4 0 0 0-4-4z");
}

:global(.jkkarl48q) {
  fill: var(--svg-color--289728, #289728);
  d: path("M0 18h36v6.5H0z");
}

:global(.l3nd-xz_s) {
  fill: var(--svg-color--ffce00, #FFCE00);
  d: path("M6.878 7.612l-.68-2.094l-.681 2.094H3.316l1.781 1.294L4.417 11l1.781-1.294L7.979 11l-.681-2.094L9.08 7.612z");
}

:global(.p4mxzbu9q) {
  fill: var(--svg-color--ffce00, #FFCE00);
  d: path("M0 24.5V27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-2.5H0z");
}

</style>
