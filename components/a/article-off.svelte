<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2i14cbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2i14cbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:article-off" {...props}></Icon>
