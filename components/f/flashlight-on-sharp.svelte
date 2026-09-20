<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4tfgcc-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:flashlight-on-sharp" {...props}></Icon>
<style>
:global(.q4tfgcc-y) {
  fill: currentColor;
  d: path("M6 5V2h12v3zm7.063 10.063q.437-.438.437-1.063t-.437-1.062T12 12.5t-1.062.438T10.5 14t.438 1.063T12 15.5t1.063-.437M8 22V11L6 8V7h12v1l-2 3v11z");
}

</style>
