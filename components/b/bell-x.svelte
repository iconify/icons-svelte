<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxf8udb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxf8udb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bell-x" {...props}></Icon>
