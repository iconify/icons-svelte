<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xboe5vb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xboe5vb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:heart-fill-24" {...props}></Icon>
