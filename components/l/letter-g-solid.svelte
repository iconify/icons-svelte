<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd-cpmb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd-cpmb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-g-solid" {...props}></Icon>
