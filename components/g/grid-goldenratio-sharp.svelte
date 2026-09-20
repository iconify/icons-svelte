<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7h6winbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:grid-goldenratio-sharp" {...props}></Icon>
<style>
:global(.p7h6winbq) {
  fill: currentColor;
  d: path("M9 22v-7H2v-2h7v-2H2V9h7V2h2v7h2V2h2v7h7v2h-7v2h7v2h-7v7h-2v-7h-2v7zm2-9h2v-2h-2z");
}

</style>
