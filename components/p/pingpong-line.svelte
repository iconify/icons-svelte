<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjh50pbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjh50pbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pingpong-line" {...props}></Icon>
