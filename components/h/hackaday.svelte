<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqo2ip6-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqo2ip6-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:hackaday" {...props}></Icon>
