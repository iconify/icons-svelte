<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccll7pbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:calendar-view-week-sharp" {...props}></Icon>
<style>
:global(.ccll7pbow) {
  fill: currentColor;
  d: path("M12.75 19V5h3.375v14zm-4.875 0V5h3.375v14zM3 19V5h3.375v14zm14.625 0V5H21v14z");
}

</style>
