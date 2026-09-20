<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqgn-lbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqgn-lbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-w-square-solid" {...props}></Icon>
