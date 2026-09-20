<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jv9mox98s"/><path class="u_66_cbxe"/><path class="o_sa-tycy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:butterflymx" {...props}></Icon>
<style>
:global(.jv9mox98s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 26.218c0-9.592-7.3-17.48-16.649-18.408A1.69 1.69 0 0 0 5.5 9.49v11.691a5.037 5.037 0 0 0 5.037 5.037z");
}

:global(.o_sa-tycy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.592 40.199C28.742 40.199 24 35.457 24 29.607v-3.39h12.428A6.07 6.07 0 0 1 42.5 32.29a7.91 7.91 0 0 1-7.908 7.909");
}

:global(.u_66_cbxe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.408 40.199c5.85 0 10.592-4.742 10.592-10.592v-3.39H11.573A6.07 6.07 0 0 0 5.5 32.29a7.91 7.91 0 0 0 7.908 7.909M24 26.218c0-9.592 7.3-17.48 16.649-18.408A1.69 1.69 0 0 1 42.5 9.49v11.691a5.037 5.037 0 0 1-5.037 5.037z");
}

</style>
