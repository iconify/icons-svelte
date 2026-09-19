<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioxzgdcvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ioxzgdcvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:emoji-flirt" {...props}></Icon>
