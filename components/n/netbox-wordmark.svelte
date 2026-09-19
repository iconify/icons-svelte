<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4b5m0bco.css';
import '../../css/s/svf4jc_ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="e4b5m0bco"/><path class="svf4jc_ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:netbox-wordmark" {...props}></Icon>
