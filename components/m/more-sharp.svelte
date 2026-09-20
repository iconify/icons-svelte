<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9awmdbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:more-sharp" {...props}></Icon>
<style>
:global(.q9awmdbvx) {
  fill: currentColor;
  d: path("m8 20l-6-8l6-8h14v16zm1-7h2v-2H9zm3.5 0h2v-2h-2zm3.5 0h2v-2h-2z");
}

</style>
