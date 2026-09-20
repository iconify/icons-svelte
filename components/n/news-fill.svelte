<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py02m_bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py02m_bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:news-fill" {...props}></Icon>
