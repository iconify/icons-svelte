<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvx6_gzou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvx6_gzou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:octagon-x" {...props}></Icon>
