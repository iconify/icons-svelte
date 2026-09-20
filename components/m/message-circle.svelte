<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy4nunbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy4nunbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:message-circle" {...props}></Icon>
