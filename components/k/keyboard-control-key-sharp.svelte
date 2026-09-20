<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpaavtb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:keyboard-control-key-sharp" {...props}></Icon>
<style>
:global(.jpaavtb5j) {
  fill: currentColor;
  d: path("M6.4 13.4L5 12l7-7l7 7l-1.4 1.4L12 7.825z");
}

</style>
