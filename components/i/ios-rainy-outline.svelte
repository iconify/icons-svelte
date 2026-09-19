<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdcpxjb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pdcpxjb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-rainy-outline" {...props}></Icon>
