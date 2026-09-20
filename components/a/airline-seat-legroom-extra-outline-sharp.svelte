<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="buf2o5bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:airline-seat-legroom-extra-outline-sharp" {...props}></Icon>
<style>
:global(.buf2o5bsv) {
  fill: currentColor;
  d: path("M13 17H2V3h2v12h9zm5.4 4L15 14H5.5V3h6v6h4.225l3.975 8.1l2.45-1.125l1.425 2.625z");
}

</style>
