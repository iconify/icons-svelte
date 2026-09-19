<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bkct20jdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kanopy" {...props}></Icon>
<style>
:global(.bkct20jdy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.32 5.112l6.324-.612v39m8.073-24.623h11.152M16.644 34.391l15.557-15.514m-9.81 9.783l12.345 14.789m-8.135 0H37.68m-16.918.051H10.32");
}

</style>
