<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pufgc7bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:invert-colors-outline" {...props}></Icon>
<style>
:global(.pufgc7bqx) {
  fill: currentColor;
  d: path("M12 21q-3.325 0-5.663-2.312T4 13.1q0-1.65.625-3.05t1.725-2.5L12 2l5.65 5.55q1.1 1.1 1.725 2.5T20 13.1q0 3.275-2.337 5.588T12 21m0-2V4.8L7.75 9q-.875.825-1.312 1.863T6 13.1q0 2.425 1.75 4.163T12 19");
}

</style>
