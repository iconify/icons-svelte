<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk8jrhbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk8jrhbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-up-square-solid" {...props}></Icon>
