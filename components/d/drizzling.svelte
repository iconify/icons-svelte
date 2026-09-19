<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqv79xbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qqv79xbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:drizzling" {...props}></Icon>
