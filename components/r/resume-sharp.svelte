<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gd2i9y3qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:resume-sharp" {...props}></Icon>
<style>
:global(.gd2i9y3qw) {
  fill: currentColor;
  d: path("M6 18V6h2v12zm4 0l10-6l-10-6z");
}

</style>
