<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a05ngs8sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a05ngs8sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:internet-explorer" {...props}></Icon>
