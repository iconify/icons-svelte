<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbyzct5is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="xbyzct5is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:day" {...props}></Icon>
