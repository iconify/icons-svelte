<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yenxbdjsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":910,"height":1026};
const content = `<path class="yenxbdjsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:drwho" {...props}></Icon>
