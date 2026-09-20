<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szha1du2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:picture-in-picture-medium-outline-sharp" {...props}></Icon>
<style>
:global(.szha1du2n) {
  fill: currentColor;
  d: path("M7.923 15.616V7.923h9.693v7.693zM3 19v-1h17V5h1v14z");
}

</style>
