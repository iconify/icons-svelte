<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx3cjdb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tx3cjdb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:influxdb" {...props}></Icon>
