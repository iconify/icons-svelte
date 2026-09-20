<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a34b0acmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:military-tech-sharp" {...props}></Icon>
<style>
:global(.a34b0acmk) {
  fill: currentColor;
  d: path("m8.9 22l1.2-3.8L7 16h3.8l.7-2.3L7 11.05V2h10v9.05l-4.5 2.65l.7 2.3H17l-3.1 2.2l1.2 3.8l-3.1-2.35zM12 11.65l1-.6V4h-2v7.05z");
}

</style>
