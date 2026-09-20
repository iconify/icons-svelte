<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1g50do1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:labs-sharp" {...props}></Icon>
<style>
:global(.j1g50do1t) {
  fill: currentColor;
  d: path("M12 22q-2.075 0-3.537-1.463T7 17V8H5V2h14v6h-2v9q0 2.075-1.463 3.538T12 22m2.125-2.875Q15 18.25 15 17h-3v-2h3v-2h-3v-2h3V8H9v9q0 1.25.875 2.125T12 20t2.125-.875");
}

</style>
