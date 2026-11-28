<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo_xvzb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo_xvzb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-right-duo" {...props}></Icon>
