<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h2pby-bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:clock-lock-20-filled" {...props}></Icon>
<style>
:global(.h2pby-bys) {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1-1 15.938V14a2 2 0 0 0-1.5-1.937V12a3 3 0 0 0-5.493-1.669A8 8 0 0 1 10 2m-.5 3a.5.5 0 0 0-.5.5v5l.008.09A.5.5 0 0 0 9.5 11h3l.09-.008A.5.5 0 0 0 12.5 10H10V5.5l-.008-.09A.5.5 0 0 0 9.5 5m-7 7v1H2a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1v-4a1 1 0 0 0-1-1h-.5v-1a2 2 0 1 0-4 0m1 1v-1a1 1 0 1 1 2 0v1zm1 2.25a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
