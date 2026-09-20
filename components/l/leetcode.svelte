<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow8xy2bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ow8xy2bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:leetcode" {...props}></Icon>
