<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zijk06bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:crop-9-16-rounded" {...props}></Icon>
<style>
:global(.zijk06bpf) {
  fill: currentColor;
  d: path("M9.616 20q-.691 0-1.153-.462T8 18.384V5.616q0-.691.463-1.153T9.616 4h4.769q.69 0 1.153.463T16 5.616v12.769q0 .69-.462 1.153T14.385 20z");
}

</style>
