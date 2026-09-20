<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epm8vz4jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:emoji-surprise-24-filled" {...props}></Icon>
<style>
:global(.epm8vz4jq) {
  fill: currentColor;
  d: path("M12 2.004c5.523 0 10 4.477 10 10s-4.477 10-10 10s-10-4.477-10-10s4.477-10 10-10m0 10.995a2.25 2.25 0 1 0 0 4.5a2.25 2.25 0 0 0 0-4.5M9 8.75a1.25 1.25 0 1 0 0 2.499A1.25 1.25 0 0 0 9 8.75m6 0a1.25 1.25 0 1 0 0 2.499a1.25 1.25 0 0 0 0-2.499");
}

</style>
