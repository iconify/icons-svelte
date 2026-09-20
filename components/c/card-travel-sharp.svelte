<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jggx_ob-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:card-travel-sharp" {...props}></Icon>
<style>
:global(.jggx_ob-x) {
  fill: currentColor;
  d: path("M3 20V7h5V3.77h8V7h5v13zM9 7h6V4.77H9zm-5 9.577h16v-2.154H4z");
}

</style>
