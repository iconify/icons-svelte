<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu-8o6bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu-8o6bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-j-octagon-solid" {...props}></Icon>
