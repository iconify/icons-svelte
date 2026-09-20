<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxooj1cdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxooj1cdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fat-corner-right-down" {...props}></Icon>
