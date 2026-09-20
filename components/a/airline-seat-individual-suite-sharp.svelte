<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub12h74_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:airline-seat-individual-suite-sharp" {...props}></Icon>
<style>
:global(.ub12h74_q) {
  fill: currentColor;
  d: path("M2 16V8h1v7h8.5V8H22v8zm6.5-3.502q.616-.618.616-1.5T8.498 9.5t-1.5-.615t-1.498.617t-.615 1.5t.617 1.498t1.5.616t1.498-.618");
}

</style>
