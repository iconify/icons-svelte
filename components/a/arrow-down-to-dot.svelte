<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwcs5xqli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwcs5xqli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-down-to-dot" {...props}></Icon>
