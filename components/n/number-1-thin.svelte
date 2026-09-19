<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s74hacqej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s74hacqej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-1-thin" {...props}></Icon>
