<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qkxe90bfg"/><path class="z9lqp6bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mysolaredge" {...props}></Icon>
<style>
:global(.qkxe90bfg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.706 11.006L5.5 36.995h30.037l6.963-25.99z");
}

:global(.z9lqp6bae) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.184 15.013l-9.852 10.491h4.076l-2.279 7.127l9.627-10.195h-4.14z");
}

</style>
