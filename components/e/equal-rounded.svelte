<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ordolsvaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:equal-rounded" {...props}></Icon>
<style>
:global(.ordolsvaj) {
  fill: currentColor;
  d: path("M5.5 17q-.625 0-1.062-.437T4 15.5t.438-1.062T5.5 14h13q.625 0 1.063.438T20 15.5t-.437 1.063T18.5 17zm0-7q-.625 0-1.062-.437T4 8.5t.438-1.062T5.5 7h13q.625 0 1.063.438T20 8.5t-.437 1.063T18.5 10z");
}

</style>
