<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmp0c2bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmp0c2bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cookie" {...props}></Icon>
