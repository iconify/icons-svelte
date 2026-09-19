<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="cz1q2ab_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:black-large-square" {...props}></Icon>
<style>
:global(.cz1q2ab_l) {
  fill: var(--svg-color--354a54, #354a54);
  d: path("M63.998 57.1a6.9 6.9 0 0 1-6.899 6.903h-50.2A6.9 6.9 0 0 1 .003 57.1V6.9C.003 3.09 3.091 0 6.899 0h50.2a6.9 6.9 0 0 1 6.899 6.9z");
}

</style>
