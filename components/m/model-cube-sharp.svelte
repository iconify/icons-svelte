<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hkdq4jb_w"/><path class="ku9hkac5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:model-cube-sharp" {...props}></Icon>
<style>
:global(.hkdq4jb_w) {
  d: path("m13.1 3.35l6.05 3.3l1.1.6v9.5l-1.1.6l-6.05 3.3l-1.1.6l-1.1-.6l-6.05-3.3l-1.1-.6v-9.5l1.1-.6l6.05-3.3l1.1-.6z");
}

:global(.ku9hkac5i) {
  d: path("m3.75 7.25l8.25 4.5l8.25-4.5M12 11.75v9.5M7.9 12.7l.29 2.11l2.11.29l-2.11.29l-.29 2.11l-.29-2.11l-2.11-.29l2.11-.29z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
