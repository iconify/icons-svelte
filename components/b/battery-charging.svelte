<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1ao6026r.css';
import '../../css/c/cf3z5jfwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1ao6026r"/><path class="cf3z5jfwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:battery-charging" {...props}></Icon>
