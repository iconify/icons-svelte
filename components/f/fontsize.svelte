<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jksem8keo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="jksem8keo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:fontsize" {...props}></Icon>
