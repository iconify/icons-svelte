<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":321};
const content = `<path class="tc6a7cgjq"/><path class="szzvwjxbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:opencode-icon" {...props}></Icon>
<style>
:global(.szzvwjxbw) {
  fill: var(--svg-color--211e1e, #211e1e);
  d: path("M192.001 64.072H63.999v192.214h128.002zM256 320.357H0V0h256z");
}

:global(.tc6a7cgjq) {
  fill: var(--svg-color--cfcecd, #cfcecd);
  d: path("M191.985 256.287H63.983V128.144h128.002z");
}

</style>
