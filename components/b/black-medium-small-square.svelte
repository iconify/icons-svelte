<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="fb3_dhlcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:black-medium-small-square" {...props}></Icon>
<style>
:global(.fb3_dhlcc) {
  fill: currentColor;
  d: path("M12 12h40v40H12z");
}

</style>
