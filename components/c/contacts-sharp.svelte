<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg_x-cbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:contacts-sharp" {...props}></Icon>
<style>
:global(.tg_x-cbev) {
  fill: currentColor;
  d: path("M4.5 21.385v-1h15v1zm0-17.77v-1h15v1zM11.998 14q1.04 0 1.771-.728t.731-1.77t-.728-1.771T12.002 9t-1.771.729t-.731 1.769t.729 1.771t1.769.731M3 19V5h18v14zm4.058-1h9.884q-1.125-1.016-2.36-1.508T12 16t-2.583.492T7.057 18");
}

</style>
