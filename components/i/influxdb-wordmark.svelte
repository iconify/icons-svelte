<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeiup5blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="eeiup5blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:influxdb-wordmark" {...props}></Icon>
