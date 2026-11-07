<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/y_tv_8b3w.css';
import '../../css/d/d0h1ndbsd.css';
import '../../css/l/l1843dc6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y_tv_8b3w"/><path class="d0h1ndbsd"/><path class="l1843dc6q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-output-broken" {...props}></Icon>
