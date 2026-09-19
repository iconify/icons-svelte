<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="phm49tbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:black-circle" {...props}></Icon>
<style>
:global(.phm49tbyx) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--3e4347, #3e4347);
}

</style>
