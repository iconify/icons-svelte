<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccc8p6bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccc8p6bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:drill-check" {...props}></Icon>
