<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kghai3b_c"/><path class="j-tkk1buy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:grievance" {...props}></Icon>
<style>
:global(.j-tkk1buy) {
  d: path("m5.5 17l-2 4.5L9 18.75M12 7.5v3.75m0 3h.01");
}

:global(.kghai3b_c) {
  d: path("m12 1.75l2.24 2.355l3.197-.588l.428 3.222l2.932 1.403L19.25 11l1.547 2.858l-2.932 1.403l-.428 3.222l-3.197-.588L12 20.25l-2.24-2.355l-3.197.588l-.428-3.222l-2.932-1.403L4.75 11L3.203 8.142l2.932-1.403l.428-3.222l3.197.588Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
