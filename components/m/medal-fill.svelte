<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbunz6bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbunz6bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:medal-fill" {...props}></Icon>
