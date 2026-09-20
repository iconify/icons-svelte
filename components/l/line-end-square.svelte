<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi8qtf5tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:line-end-square" {...props}></Icon>
<style>
:global(.zi8qtf5tx) {
  fill: currentColor;
  d: path("M12.577 15.923V12.5h-9.5v-1h9.5V8.077h7.846v7.846z");
}

</style>
