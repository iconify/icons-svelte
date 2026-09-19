<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywr37pcaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":29,"height":24};
const content = `<path class="ywr37pcaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:left-align" {...props}></Icon>
