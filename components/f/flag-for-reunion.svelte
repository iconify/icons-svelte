<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="bb5xqnbcm"/><path class="goh97o8ew"/><path class="xo_26knux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-reunion" {...props}></Icon>
<style>
:global(.bb5xqnbcm) {
  fill: var(--svg-color--36f, #36F);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4z");
}

:global(.goh97o8ew) {
  fill: var(--svg-color--red, red);
  d: path("M18 18L1.368 30.012l.001.001A3.983 3.983 0 0 0 4 31h28a3.984 3.984 0 0 0 2.632-.988L18 18z");
}

:global(.xo_26knux) {
  fill: var(--svg-color--ff0, #FF0);
  d: path("M18 18.019l18 1.487v-2.975zM0 16.531v2.975l18-1.487zm2.405-11.2A4.01 4.01 0 0 0 .404 7.247L18 18L2.406 5.33l-.001.001zm33.191 1.916a4.023 4.023 0 0 0-2.003-1.917L18 18L35.596 7.247zM19.5 5h-3L18 18z");
}

</style>
