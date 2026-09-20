<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="q3ncj0etc"/><circle class="nbtmwvp6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:radio-button" {...props}></Icon>
<style>
:global(.nbtmwvp6k) {
  cx: 18px;
  cy: 18px;
  r: 8px;
  fill: var(--svg-color--bbddf5, #bbddf5);
}

:global(.q3ncj0etc) {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--269, #269);
}

</style>
