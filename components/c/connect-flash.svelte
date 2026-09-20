<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiv1_8bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yiv1_8bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:connect-flash" {...props}></Icon>
