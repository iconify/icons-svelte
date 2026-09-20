<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g clip-rule="evenodd" class="utxjc7b5q"><path class="e-4uhbt6a"/><path class="ykd2hbt2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:envelope" {...props}></Icon>
<style>
:global(.e-4uhbt6a) {
  d: path("M20.97 50.92v45.02h86.06V50.92L64 72.31z");
}

:global(.utxjc7b5q) {
  fill: var(--svg-color--fcc21b, #fcc21b);
  fill-rule: evenodd;
}

:global(.ykd2hbt2n) {
  d: path("M20.97 32.06v11.98L64 65.43l43.03-21.39V32.06z");
}

</style>
