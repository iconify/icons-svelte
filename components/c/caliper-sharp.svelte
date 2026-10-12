<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrapg1sto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:caliper-sharp" {...props}></Icon>
<style>
:global(.xrapg1sto) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.5h18.5v4H2.75zm9.25 0v1.75m3-1.75v1.75m3-1.75v1.75M3.5 8.5H6v10l-.23-.71l-2.79-8.58l-.23-.71zm6.25 0h2.5l-.23.71l-2.79 8.58l-.23.71v-10z");
}

</style>
