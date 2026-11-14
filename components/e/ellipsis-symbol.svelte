<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi733pbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:ellipsis-symbol" {...props}></Icon>
<style>
:global(.bi733pbad) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 17q0-1.75 1.75-1.75T7.25 17T5.5 18.75T3.75 17M12 15.25q-1.75 0-1.75 1.75T12 18.75T13.75 17T12 15.25M16.75 17q0-1.75 1.75-1.75T20.25 17t-1.75 1.75T16.75 17");
}

</style>
