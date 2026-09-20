<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1c-rtbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:change-history-rounded" {...props}></Icon>
<style>
:global(.z1c-rtbqo) {
  fill: currentColor;
  d: path("M5.262 19q-.48 0-.702-.416q-.223-.417.025-.82l6.738-10.78q.243-.378.677-.378t.677.378l6.739 10.78q.248.403.025.82q-.224.416-.703.416z");
}

</style>
