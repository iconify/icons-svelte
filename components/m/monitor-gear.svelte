<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwajsxbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwajsxbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:monitor-gear" {...props}></Icon>
