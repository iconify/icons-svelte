<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nuv41mbuh"/><path class="bxa-uqymt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bridal-shower" {...props}></Icon>
<style>
:global(.bxa-uqymt) {
  d: path("M18 21.25L15 18a1.9 1.9 0 0 1 3-2.25A1.9 1.9 0 0 1 21 18Z");
}

:global(.nuv41mbuh) {
  d: path("M3 5.5h18v4H3ZM12.4 19H4.5V9.5h15v2.8M12 5.5v10.4m0 1.9V19m0-13.5C10.5 2 6.5 2 7 4c.3 1.2 2.5 1.5 5 1.5Zm0 0C13.5 2 17.5 2 17 4c-.3 1.2-2.5 1.5-5 1.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
