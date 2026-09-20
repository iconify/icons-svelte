<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGupXZghCZ)" class="vo9_wwxbz"/><path fill="url(#SVGupXZghCZ)" class="wj10zbmhe"/><defs><linearGradient id="SVGupXZghCZ" x1="7.018" x2="14.761" y1="5.009" y2="19.656" gradientUnits="userSpaceOnUse"><stop class="s6k9lqbcf"/><stop offset=".19" class="jqobbj6lr"/><stop offset=".45" class="a_vge2bdv"/><stop offset=".69" class="iccw4bcpx"/><stop offset=".79" class="mkx4gzb-k"/><stop offset=".9" class="bvlvo7u-q"/><stop offset="1" class="lh5wz7bqm"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:aart" {...props}></Icon>
<style>
:global(.a_vge2bdv) {
  stop-color: var(--svg-color--67bbce, #67bbce);
}

:global(.bvlvo7u-q) {
  stop-color: var(--svg-color--e08c94, #e08c94);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.iccw4bcpx) {
  stop-color: var(--svg-color--382f4a, #382f4a);
}

:global(.jqobbj6lr) {
  stop-color: var(--svg-color--3b578e, #3b578e);
}

:global(.lh5wz7bqm) {
  stop-color: var(--svg-color--ce7782, #ce7782);
}

:global(.mkx4gzb-k) {
  stop-color: var(--svg-color--a22b2c, #a22b2c);
}

:global(.s6k9lqbcf) {
  stop-color: var(--svg-color--51a7dc, #51a7dc);
}

:global(.vo9_wwxbz) {
  d: path("M15.071 3.844H8.93L3 20.156h5.44l.747-2.081a3.376 3.376 0 0 1 1.8-5.074L12 10.144L13.012 13a3.375 3.375 0 0 1 1.806 5.074l.743 2.081H21z");
}

:global(.wj10zbmhe) {
  d: path("M12 18.469a2.25 2.25 0 1 0 0-4.5a2.25 2.25 0 0 0 0 4.5");
}

</style>
