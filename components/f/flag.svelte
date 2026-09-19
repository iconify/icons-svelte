<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq5ir4b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="qq5ir4b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:flag" {...props}></Icon>
