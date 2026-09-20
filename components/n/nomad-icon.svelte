<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":296};
const content = `<path class="dn-uczblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:nomad-icon" {...props}></Icon>
<style>
:global(.dn-uczblj) {
  fill: var(--svg-color--00ca8e, #00ca8e);
  d: path("M128.044 0L0 73.865v147.773l127.956 73.865L256 221.638V73.865zm57.123 162.582l-34.098 19.685l-41.217-22.542v47.105L71.14 231.393v-98.428l30.76-18.806l42.622 22.453V88.541l40.645-24.431z");
}

</style>
