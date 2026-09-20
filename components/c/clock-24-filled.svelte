<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cisrnxwqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:clock-24-filled" {...props}></Icon>
<style>
:global(.cisrnxwqx) {
  fill: currentColor;
  d: path("M15.25 13.5h-4a.75.75 0 0 1-.75-.75v-6a.75.75 0 0 1 1.5 0V12h3.25a.75.75 0 0 1 0 1.5M12 2C6.478 2 2 6.478 2 12s4.478 10 10 10s10-4.478 10-10S17.522 2 12 2");
}

</style>
