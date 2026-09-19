<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf1qidbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yf1qidbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-football-outline" {...props}></Icon>
