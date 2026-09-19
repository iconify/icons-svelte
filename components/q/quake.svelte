<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yboa2tbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="yboa2tbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:quake" {...props}></Icon>
