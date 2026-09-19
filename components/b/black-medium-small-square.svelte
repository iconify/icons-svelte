<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="nb38wbbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:black-medium-small-square" {...props}></Icon>
<style>
:global(.nb38wbbdj) {
  fill: var(--svg-color--333, #333);
  d: path("M12 12h40v40H12z");
}

</style>
