<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_h7tfngl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:mobile-charge-sharp" {...props}></Icon>
<style>
:global(.t_h7tfngl) {
  fill: currentColor;
  d: path("m11.577 16.23l2.539-5.076h-1.693V7.769l-2.538 5.077h1.692zM6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
