<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="uks4d112d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:number-circle-four-fill" {...props}></Icon>
<style>
:global(.uks4d112d) {
  fill: currentColor;
  d: path("M104.36 144L136 103.32V144ZM232 128A104 104 0 1 1 128 24a104.11 104.11 0 0 1 104 104m-64 24a8 8 0 0 0-8-8h-8V80a8 8 0 0 0-14.31-4.91l-56 72A8 8 0 0 0 88 160h48v16a8 8 0 0 0 16 0v-16h8a8 8 0 0 0 8-8");
}

</style>
