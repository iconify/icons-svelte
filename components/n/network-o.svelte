<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcexz4vvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vcexz4vvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:network-o" {...props}></Icon>
