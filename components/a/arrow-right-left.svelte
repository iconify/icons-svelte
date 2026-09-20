<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxucp5bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxucp5bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-right-left" {...props}></Icon>
