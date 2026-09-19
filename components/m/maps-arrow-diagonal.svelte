<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9v157lcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9v157lcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:maps-arrow-diagonal" {...props}></Icon>
