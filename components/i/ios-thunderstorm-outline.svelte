<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck9j7l_ys.css';
import '../../css/y/yu7vi3bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ck9j7l_ys"/><path class="yu7vi3bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-thunderstorm-outline" {...props}></Icon>
