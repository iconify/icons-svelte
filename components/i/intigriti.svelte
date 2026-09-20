<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj586r4go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yj586r4go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:intigriti" {...props}></Icon>
