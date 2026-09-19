<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgc4y1zlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgc4y1zlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-down-1-thin" {...props}></Icon>
