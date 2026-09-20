<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytzgxbc7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ytzgxbc7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:magsafe-solid" {...props}></Icon>
