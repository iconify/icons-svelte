<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i__vh5p7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i__vh5p7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:logstash-output" {...props}></Icon>
