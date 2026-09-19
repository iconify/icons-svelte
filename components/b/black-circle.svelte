<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="kxvuyd7py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:black-circle" {...props}></Icon>
<style>
:global(.kxvuyd7py) {
  fill: var(--svg-color--354a54, #354a54);
  d: path("M57.55 14.451c9.694 14.11 6.109 33.406-7.999 43.1c-14.11 9.695-33.408 6.112-43.1-7.999c-9.693-14.11-6.112-33.41 8-43.1c14.11-9.692 33.408-6.109 43.1 8");
}

</style>
