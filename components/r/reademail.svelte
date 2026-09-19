<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmk_yopdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="xmk_yopdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:reademail" {...props}></Icon>
