<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo3wz3hzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:office-apps-24-regular" {...props}></Icon>
<style>
:global(.yo3wz3hzp) {
  fill: currentColor;
  d: path("M12 17.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m7 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m-14 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m7-7a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m7 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m-14 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m7-7a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m7 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m-14 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
