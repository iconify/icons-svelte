<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsq7xeoxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="xsq7xeoxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:progress-3" {...props}></Icon>
