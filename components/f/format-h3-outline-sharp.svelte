<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_yb00bqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-h3-outline-sharp" {...props}></Icon>
<style>
:global(.m_yb00bqv) {
  fill: currentColor;
  d: path("M3 17V7h2v4h4V7h2v10H9v-4H5v4zm10 0v-2h6v-2h-4v-2h4V9h-6V7h6q.825 0 1.413.588T21 9v6q0 .825-.587 1.413T19 17z");
}

</style>
