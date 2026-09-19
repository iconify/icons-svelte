<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peuflhigh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="peuflhigh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:data-transfer-both" {...props}></Icon>
