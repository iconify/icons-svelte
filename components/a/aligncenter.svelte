<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srz6vzznd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":644};
const content = `<path class="srz6vzznd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:aligncenter" {...props}></Icon>
