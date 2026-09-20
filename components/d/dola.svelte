<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="zski_4z5u"><path clip-rule="evenodd" class="vz00b8ble"/><path class="n3li3cb4w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:dola" {...props}></Icon>
<style>
:global(.n3li3cb4w) {
  d: path("M13.406 3h2.312L9.25 21H6.937zm3.375 0h2.312l-6.469 18h-2.312z");
}

:global(.vz00b8ble) {
  fill-rule: evenodd;
  d: path("M12.563 4.125h-3.05L4.126 18.75h8.438a7.314 7.314 0 0 0 0-14.625m0 1.687h-1.688l-4.219 11.25h5.907a5.625 5.625 0 0 0 0-11.25");
}

:global(.zski_4z5u) {
  fill: var(--svg-color--ffbb51, #ffbb51);
}

</style>
