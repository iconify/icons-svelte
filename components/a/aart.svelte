<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq8x9dh3q.css';
import '../../css/m/mvqgwxqkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq8x9dh3q"/><path class="mvqgwxqkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:aart" {...props}></Icon>
