<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngkdydb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ngkdydb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-803" {...props}></Icon>
