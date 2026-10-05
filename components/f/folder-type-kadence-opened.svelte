<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nhauxx5yr"/><path class="xw8mnvrvp"/><rect class="gw3pv5fcu"/><path class="yo9zh7bbx"/><circle class="p5l0i8bez"/><circle class="kfom7cc5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:folder-type-kadence-opened" {...props}></Icon>
<style>
:global(.gw3pv5fcu) {
  width: 20px;
  height: 20px;
  x: 11px;
  y: 11px;
  fill: var(--svg-color--0e6e6e, #0e6e6e);
  rx: 4.4px;
}

:global(.kfom7cc5r) {
  cx: 25.75px;
  cy: 23.25px;
  r: 1.5px;
  fill: var(--svg-color--fff, #fff);
}

:global(.nhauxx5yr) {
  fill: var(--svg-color--4fc7c0, #4fc7c0);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

:global(.p5l0i8bez) {
  cx: 25.75px;
  cy: 18.75px;
  r: 1.5px;
  fill: var(--svg-color--fff, #fff);
}

:global(.xw8mnvrvp) {
  fill: var(--svg-color--4fc7c0, #4fc7c0);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

:global(.yo9zh7bbx) {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.5 15h4v12h-4zm6 0h1.75v12H20.5z");
}

</style>
