<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmvo8lspr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmvo8lspr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:openai" {...props}></Icon>
