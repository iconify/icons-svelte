<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcmt7s_3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcmt7s_3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:issuu" {...props}></Icon>
