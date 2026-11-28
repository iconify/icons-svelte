<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpt0mldnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpt0mldnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:folder-search" {...props}></Icon>
