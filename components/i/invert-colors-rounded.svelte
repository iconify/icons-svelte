<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9tc9eict"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:invert-colors-rounded" {...props}></Icon>
<style>
:global(.g9tc9eict) {
  fill: currentColor;
  d: path("M12 20q-2.921 0-4.96-2.002T5 13.125q0-1.477.558-2.687t1.484-2.196l4.12-4.025q.186-.18.403-.264T12 3.869t.435.084t.403.264l4.12 4.025q.927.985 1.484 2.224q.558 1.24.558 2.659q0 2.871-2.04 4.873T12 20m0-1V4.8L7.75 9q-.875.825-1.312 1.875T6 13.125q0 2.425 1.75 4.15T12 19");
}

</style>
