<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5cqvibbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:ark" {...props}></Icon>
<style>
:global(.h5cqvibbu) {
  fill: var(--svg-color--f70000, #f70000);
  d: path("M11.959 9.804L3 19.367l9-14.824l9 14.914zm-1.505 3.739L11.894 12l1.366 1.543zm-2.602 2.571l1.595-1.543h4.844l1.636 1.543z");
}

</style>
