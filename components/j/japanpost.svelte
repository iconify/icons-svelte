<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsdixyb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsdixyb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:japanpost" {...props}></Icon>
