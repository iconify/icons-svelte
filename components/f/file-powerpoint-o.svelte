<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8nsyd_1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="j8nsyd_1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:file-powerpoint-o" {...props}></Icon>
