<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhfwdgasf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhfwdgasf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:other-watching-movie" {...props}></Icon>
