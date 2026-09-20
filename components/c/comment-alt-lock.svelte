<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5r9tz_qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5r9tz_qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-alt-lock" {...props}></Icon>
