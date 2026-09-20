<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxpg19b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jxpg19b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:commercial-building" {...props}></Icon>
