<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dauc8q9yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dauc8q9yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:liberapay" {...props}></Icon>
