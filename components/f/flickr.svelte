<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0hzh0sbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0hzh0sbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:flickr" {...props}></Icon>
