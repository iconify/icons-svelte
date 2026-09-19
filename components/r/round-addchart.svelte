<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjlss7y5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-addchart" {...props}></Icon>
<style>
:global(.hjlss7y5l) {
  fill: currentColor;
  d: path("M11 10c0-.55.45-1 1-1s1 .45 1 1v7h-2zm9 3c-.55 0-1 .45-1 1v5H5V5h5c.55 0 1-.45 1-1s-.45-1-1-1H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2v-5c0-.55-.45-1-1-1m1-8h-2V3c0-.55-.45-1-1-1s-1 .45-1 1v2h-2c-.55 0-1 .45-1 1s.45 1 1 1h2v2c0 .55.45 1 1 1s1-.45 1-1V7h2c.55 0 1-.45 1-1s-.45-1-1-1m-5 8c-.55 0-1 .45-1 1v3h2v-3c0-.55-.45-1-1-1m-9-1v5h2v-5c0-.55-.45-1-1-1s-1 .45-1 1");
}

</style>
