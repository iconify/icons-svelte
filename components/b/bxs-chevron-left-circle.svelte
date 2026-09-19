<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt9nwbbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt9nwbbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chevron-left-circle" {...props}></Icon>
