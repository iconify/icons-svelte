<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmdukbb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-insert-outline-sharp" {...props}></Icon>
<style>
:global(.nmdukbb3i) {
  fill: currentColor;
  d: path("M17.812 17.289L7.712 7.208V16.5h-1v-11h11v1H8.419L18.5 16.6z");
}

</style>
