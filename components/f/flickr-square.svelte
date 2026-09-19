<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqw5sgesf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqw5sgesf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:flickr-square" {...props}></Icon>
