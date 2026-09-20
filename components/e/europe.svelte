<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9c4pl6ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="w9c4pl6ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:europe" {...props}></Icon>
