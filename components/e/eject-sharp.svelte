<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx5h6vmwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:eject-sharp" {...props}></Icon>
<style>
:global(.xx5h6vmwk) {
  fill: currentColor;
  d: path("M6.154 18.346v-.923h11.692v.923zm.158-3.692L12 6.154l5.689 8.5z");
}

</style>
