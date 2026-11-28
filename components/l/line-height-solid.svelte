<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbly7ysou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbly7ysou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:line-height-solid" {...props}></Icon>
