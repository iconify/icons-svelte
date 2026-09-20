<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi9tzv3au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wi9tzv3au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:logstash-filter" {...props}></Icon>
