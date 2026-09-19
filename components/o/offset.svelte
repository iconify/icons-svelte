<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phjcr-75y.css';
import '../../css/i/iqsh6wb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="phjcr-75y"/><path class="iqsh6wb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:offset" {...props}></Icon>
