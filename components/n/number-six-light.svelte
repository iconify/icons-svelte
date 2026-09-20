<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ao5ne2b9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:number-six-light" {...props}></Icon>
<style>
:global(.ao5ne2b9r) {
  fill: currentColor;
  d: path("M128 106a53.7 53.7 0 0 0-19.94 3.83L141.23 51a6 6 0 1 0-10.46-5.89l-49.54 88A54 54 0 1 0 128 106m0 96a42 42 0 1 1 42-42a42 42 0 0 1-42 42");
}

</style>
