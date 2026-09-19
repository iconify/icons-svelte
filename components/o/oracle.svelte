<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw8bn4bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iw8bn4bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:oracle" {...props}></Icon>
