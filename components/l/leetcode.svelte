<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmmwgqbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmmwgqbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:leetcode" {...props}></Icon>
