<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="u-85q7evm"/><path class="nlddcxuws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:flag-for-somalia" {...props}></Icon>
<style>
:global(.nlddcxuws) {
  fill: var(--svg-color--fff, #fff);
  d: path("m32 39.2l9.9 7.1l-3.8-11.5l9.9-7.1H35.8L32 16.3l-3.8 11.4H16l9.8 7.1l-3.7 11.5z");
}

:global(.u-85q7evm) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--42ade2, #42ade2);
}

</style>
