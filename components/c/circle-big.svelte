<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="b9r-16fsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:circle-big" {...props}></Icon>
<style>
:global(.b9r-16fsm) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 2.5a7.5 7.5 0 1 0 0 15a7.5 7.5 0 0 0 0-15M.5 10a9.5 9.5 0 1 1 19 0a9.5 9.5 0 0 1-19 0");
}

</style>
