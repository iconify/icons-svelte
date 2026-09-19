<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynum6zy-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynum6zy-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-down-3-square-bold" {...props}></Icon>
