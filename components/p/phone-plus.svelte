<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqge86tid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqge86tid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:phone-plus" {...props}></Icon>
