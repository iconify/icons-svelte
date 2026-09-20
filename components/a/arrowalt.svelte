<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn7-dbh4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hn7-dbh4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:arrowalt" {...props}></Icon>
