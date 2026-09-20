<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf3ykrb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf3ykrb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-tick-outline" {...props}></Icon>
