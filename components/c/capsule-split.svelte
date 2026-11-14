<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz883kx8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:capsule-split" {...props}></Icon>
<style>
:global(.zz883kx8p) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m9.22 9.22l5-5q.054-.055.119-.097q2.721-1.785 5.022.516t.516 5.022q-.042.065-.097.119l-5 5l-5 5q-.054.055-.119.097q-2.721 1.785-5.022-.516t-.516-5.022q.042-.065.097-.119z");
}

</style>
