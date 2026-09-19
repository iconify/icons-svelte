<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbpddbcjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1188,"height":1000};
const content = `<path class="xbpddbcjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:logout" {...props}></Icon>
