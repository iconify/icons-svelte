<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykb8jd99p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykb8jd99p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:message-square-off" {...props}></Icon>
