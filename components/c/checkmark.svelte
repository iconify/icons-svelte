<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="k8fiy6bnz"/><path class="wtkeqgbos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:checkmark" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.k8fiy6bnz) {
  d: path("m15.374 5.986l-5 9c-.647 1.165-2.396.194-1.748-.972l5-9c.647-1.165 2.396-.194 1.748.972");
}

:global(.wtkeqgbos) {
  d: path("m5.125 9.72l5 4c1.04.832-.209 2.394-1.25 1.56l-5-4c-1.04-.832.209-2.394 1.25-1.56");
}

</style>
