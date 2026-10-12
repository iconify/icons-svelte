<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egf2uhb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fast-forward-circle-sharp" {...props}></Icon>
<style>
:global(.egf2uhb-a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.98 6.61l6.54 4.53l1.23.86l-1.23.86l-6.54 4.53l-1.23.86V5.75zm9.5 0l6.54 4.53l1.23.86l-1.23.86l-6.54 4.53l-1.23.86V5.75z");
}

</style>
