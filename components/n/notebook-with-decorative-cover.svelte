<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="pf7x-ccdt"/><path class="llpo365nn"/><path class="l_m7g57lm"/><path class="d_4yvcbrq"/><path class="b7lv92v_m"/><path class="c99-g3uuo"/><path class="w6vjn_bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:notebook-with-decorative-cover" {...props}></Icon>
<style>
:global(.b7lv92v_m) {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M29 32a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V12a4 4 0 0 1 4-4h19.335C27.544 8 29 9.456 29 11.665z");
}

:global(.c99-g3uuo) {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M6 6C4.312 6 4.269 4.078 5 3.25C5.832 2.309 7.125 2 9.438 2H11V0H8.281C4.312 0 1 2.5 1 5.375V32a4 4 0 0 0 4 4h2V6z");
}

:global(.d_4yvcbrq) {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M31 32a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V10a4 4 0 0 1 4-4h21a4 4 0 0 1 4 4z");
}

:global(.l_m7g57lm) {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M31 31a3 3 0 0 1-3 3H4a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h24a3 3 0 0 1 3 3z");
}

:global(.llpo365nn) {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M33 30a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4V6c0-4.119-.021-4 5-4h21a4 4 0 0 1 4 4z");
}

:global(.pf7x-ccdt) {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M35 26a4 4 0 0 1-4 4H5a4 4 0 0 1-4-4V6.313C1 4.104 6.791 0 9 0h20.625C32.719 0 35 2.312 35 5.375z");
}

:global(.w6vjn_bib) {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M25 18a2 2 0 0 1-2 2H13a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2z");
}

</style>
