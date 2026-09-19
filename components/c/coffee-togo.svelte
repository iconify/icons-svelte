<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxxjykb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxxjykb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:coffee-togo" {...props}></Icon>
