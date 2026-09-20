<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":192};
const content = `<path class="r63qlvx5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:crateio" {...props}></Icon>
<style>
:global(.r63qlvx5j) {
  fill: var(--svg-color--009dc7, #009dc7);
  d: path("M192 64V0h-64v64H0v64h64v64h64v-64h128V64z");
}

</style>
