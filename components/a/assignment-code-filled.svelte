<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg08ri5ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg08ri5ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:assignment-code-filled" {...props}></Icon>
