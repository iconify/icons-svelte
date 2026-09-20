<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga4go3bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ga4go3bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jeep" {...props}></Icon>
