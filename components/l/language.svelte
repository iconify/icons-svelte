<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mypu-ib1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="mypu-ib1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:language" {...props}></Icon>
