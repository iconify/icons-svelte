<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1fv-_b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:details-outline" {...props}></Icon>
<style>
:global(.z1fv-_b_d) {
  fill: currentColor;
  d: path("M3.692 20L12 5.058L20.308 20zM5.4 19h6.1V8.021zm7.1 0h6.1L12.5 8.021z");
}

</style>
