<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su8t33t5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1435,"height":1000};
const content = `<path class="su8t33t5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:cloud" {...props}></Icon>
