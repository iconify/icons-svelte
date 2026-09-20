<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znu28pc8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:hard-drive-sharp" {...props}></Icon>
<style>
:global(.znu28pc8v) {
  fill: currentColor;
  d: path("M18.063 15.563q.437-.438.437-1.063t-.437-1.062T17 13t-1.062.438T15.5 14.5t.438 1.063T17 16t1.063-.437M22 9H2l4-4h12zM2 19v-8h20v8z");
}

</style>
