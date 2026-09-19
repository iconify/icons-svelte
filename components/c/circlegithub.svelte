<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yusms--8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1007};
const content = `<path class="yusms--8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlegithub" {...props}></Icon>
