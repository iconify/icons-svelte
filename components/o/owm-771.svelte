<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izfv5sbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="izfv5sbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-771" {...props}></Icon>
