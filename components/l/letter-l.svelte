<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="v_rpozbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:letter-l" {...props}></Icon>
<style>
:global(.v_rpozbbm) {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M102.89 99.51H57.24v-82c0-1.24-1-2.24-2.24-2.24H33.11c-1.24 0-2.24 1-2.24 2.24v100.96c0 1.24 1 2.24 2.24 2.24h69.79c1.24 0 2.24-1 2.24-2.24v-16.72a2.25 2.25 0 0 0-2.25-2.24");
}

</style>
