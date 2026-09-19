<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1pv6n01g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1pv6n01g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-hdd" {...props}></Icon>
