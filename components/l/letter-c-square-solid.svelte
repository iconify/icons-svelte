<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypxxisb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypxxisb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-c-square-solid" {...props}></Icon>
