<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bp_x8abzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:circuitry-bold" {...props}></Icon>
<style>
:global(.bp_x8abzw) {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20M52 52h24v95.22a24 24 0 1 0 24 0V125l40 40v39H52Zm152 152h-40v-44a12 12 0 0 0-3.51-8.49L100 91V52h24v20a12 12 0 0 0 3.51 8.49l17.31 17.3a24 24 0 1 0 17-17L148 67V52h56Z");
}

</style>
