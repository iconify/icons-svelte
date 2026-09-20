<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jraks8bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jraks8bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cigarette-off" {...props}></Icon>
