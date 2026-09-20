<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjl1bob8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="tjl1bob8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:instant-picture" {...props}></Icon>
