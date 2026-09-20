<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1roa6qwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:mobile-check-sharp" {...props}></Icon>
<style>
:global(.t1roa6qwm) {
  fill: currentColor;
  d: path("m11.05 14.308l4.258-4.258l-.708-.708l-3.55 3.55l-1.4-1.4l-.708.708zM6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
