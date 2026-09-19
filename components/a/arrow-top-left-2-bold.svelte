<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpw2p007g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpw2p007g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-left-2-bold" {...props}></Icon>
