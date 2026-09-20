<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm3qzydqs.css';
import '../../css/y/yb0_9vbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm3qzydqs"/><path class="yb0_9vbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dotenv" {...props}></Icon>
