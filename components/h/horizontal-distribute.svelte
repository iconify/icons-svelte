<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uitdnubas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:horizontal-distribute" {...props}></Icon>
<style>
:global(.uitdnubas) {
  fill: currentColor;
  d: path("M2 22V2h2v20zm8.5-5V7h3v10zm9.5 5V2h2v20z");
}

</style>
