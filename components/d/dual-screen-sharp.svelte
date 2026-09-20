<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jizizubxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:dual-screen-sharp" {...props}></Icon>
<style>
:global(.jizizubxe) {
  fill: currentColor;
  d: path("M5 18.277V3l8 3.198v15.29zM15 18V4.842L10.392 3H19v15z");
}

</style>
