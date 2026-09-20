<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG1Y9yXddx)" class="t50-ofqtg"/><path fill="url(#SVGeAAN0dIw)" class="pulnx2ghc"/><defs><linearGradient id="SVG1Y9yXddx" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop offset=".32" class="txd956w6a"/><stop offset="1" class="ihzvlub3d"/></linearGradient><linearGradient id="SVGeAAN0dIw" x1="16.5" x2="16.5" y1="21" y2="3" gradientUnits="userSpaceOnUse"><stop offset=".46" class="wy-bpgbxh"/><stop offset="1" class="y2ljxihwb"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:dfx" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ihzvlub3d) {
  stop-color: var(--svg-color--3f28f7, #3f28f7);
}

:global(.pulnx2ghc) {
  d: path("M12 20.995V11.96l3.538 3.6c1.142-.979 1.49-2.83 1.541-3.6c0-3.066-3.06-5.203-5.079-4.984V3c7.099.338 8.96 6.115 9 8.96c0 6.323-5.45 9.18-9 9.035");
}

:global(.t50-ofqtg) {
  d: path("M12 3.006v9.033l-3.538-3.6c-1.142.979-1.49 2.83-1.541 3.6c0 3.066 3.06 5.204 5.079 4.984V21c-7.099-.337-8.96-6.114-9-8.96c0-6.323 5.45-9.18 9-9.034");
}

:global(.txd956w6a) {
  stop-color: var(--svg-color--00e8f2, #00e8f2);
}

:global(.wy-bpgbxh) {
  stop-color: var(--svg-color--ea00d1, #ea00d1);
}

:global(.y2ljxihwb) {
  stop-color: var(--svg-color--6401f2, #6401f2);
}

</style>
