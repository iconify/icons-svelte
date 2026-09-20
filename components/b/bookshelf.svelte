<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx55dmspr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx55dmspr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bookshelf" {...props}></Icon>
