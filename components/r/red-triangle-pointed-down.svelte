<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="s60d7nb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:red-triangle-pointed-down" {...props}></Icon>
<style>
:global(.s60d7nb_c) {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 62L62 2H2z");
}

</style>
