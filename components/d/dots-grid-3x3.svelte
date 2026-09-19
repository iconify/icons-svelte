<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxg0rzbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxg0rzbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:dots-grid-3x3" {...props}></Icon>
