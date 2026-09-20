<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki9nf03-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki9nf03-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:pause-waves" {...props}></Icon>
