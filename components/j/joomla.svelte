<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrf76ybrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yrf76ybrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:joomla" {...props}></Icon>
