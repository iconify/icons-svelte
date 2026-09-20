<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="ud6j34bqn"/><circle class="s4pa6gbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-bangladesh" {...props}></Icon>
<style>
:global(.s4pa6gbnv) {
  cx: 16px;
  cy: 17.5px;
  r: 7px;
  fill: var(--svg-color--f42a41, #f42a41);
}

:global(.ud6j34bqn) {
  fill: var(--svg-color--006a4d, #006a4d);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
