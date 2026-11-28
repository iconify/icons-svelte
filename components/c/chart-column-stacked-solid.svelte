<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yihlb0bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yihlb0bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-column-stacked-solid" {...props}></Icon>
