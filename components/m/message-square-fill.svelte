<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsr7wabmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsr7wabmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:message-square-fill" {...props}></Icon>
