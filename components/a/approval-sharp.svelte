<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phpxk1_wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:approval-sharp" {...props}></Icon>
<style>
:global(.phpxk1_wm) {
  fill: currentColor;
  d: path("M5 19.462v-6.077h14v6.077zm1-3h12v-2.077H6zm6-3.077L8 7.962v-.193q0-1.671 1.165-2.835Q10.329 3.769 12 3.769t2.836 1.165T16 7.769v.192z");
}

</style>
