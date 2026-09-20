<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGgUgOGbYv)" class="q2uxt_b2x"/><path fill="url(#SVGUDh47cWt)" class="h12mo0i6k"/><defs><linearGradient id="SVGgUgOGbYv" x1="6.003" x2="11.42" y1="4.444" y2="14.328" gradientUnits="userSpaceOnUse"><stop class="h4uup7b_z"/><stop offset="1" class="ndt5h9gjs"/></linearGradient><linearGradient id="SVGUDh47cWt" x1="5.229" x2="15.668" y1="5.571" y2="11.399" gradientUnits="userSpaceOnUse"><stop class="h4uup7b_z"/><stop offset="1" class="ndt5h9gjs"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:prx" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.h12mo0i6k) {
  d: path("M7.475 14.854L4.286 21l8.949-5.945L4.286 3z");
}

:global(.h4uup7b_z) {
  stop-color: var(--svg-color--f504cb, #f504cb);
}

:global(.ndt5h9gjs) {
  stop-color: var(--svg-color--3f2ea0, #3f2ea0);
}

:global(.q2uxt_b2x) {
  d: path("M19.714 8.08L4.388 3.097l6.712 9.432z");
}

</style>
