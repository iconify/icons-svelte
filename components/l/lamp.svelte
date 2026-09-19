<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz9vh5b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":448};
const content = `<path class="vz9vh5b-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:lamp" {...props}></Icon>
