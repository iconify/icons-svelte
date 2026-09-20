<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymonzhbhk.css';
import '../../css/w/wbjg6db2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ymonzhbhk"/><path class="ouiIcon__fillSecondary wbjg6db2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:ml-outlier-detection-job" {...props}></Icon>
