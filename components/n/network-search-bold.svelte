<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xltx7yb9x.css';
import '../../css/k/kogil-gfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xltx7yb9x"/><path class="kogil-gfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:network-search-bold" {...props}></Icon>
