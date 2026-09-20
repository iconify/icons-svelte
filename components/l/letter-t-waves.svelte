<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhrh62b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhrh62b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-t-waves" {...props}></Icon>
