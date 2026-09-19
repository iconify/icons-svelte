<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="c6bgvmbcy"/><path class="vretevbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:flag-for-poland" {...props}></Icon>
<style>
:global(.c6bgvmbcy) {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M32 2c16.6 0 30 13.4 30 30H2C2 15.4 15.4 2 32 2");
}

:global(.vretevbvp) {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 62C15.4 62 2 48.6 2 32h60c0 16.6-13.4 30-30 30");
}

</style>
