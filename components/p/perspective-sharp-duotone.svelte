<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="da6czn47f"/><path class="bo_kn3bdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:perspective-sharp-duotone" {...props}></Icon>
<style>
:global(.bo_kn3bdi) {
  d: path("M13 1V11H23V13H13V23H11V13H1V11H11V1H13Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.da6czn47f) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.79 4.02C19.085 3.96 19.394 4.03 19.629 4.22C19.863 4.41 20 4.7 20 5V20C19.999 20.27 19.845 20.57 19.653 20.76C19.403 20.95 19.027 21.05 18.726 20.96L4.726 16.96C4.35 16.85 4.063 16.46 4 16.08V8C4 7.53 4.33 7.12 4.79 7.02L18.79 4.02Z");
}

</style>
