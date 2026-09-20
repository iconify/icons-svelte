<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc-a-nvsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yc-a-nvsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gnu-bash" {...props}></Icon>
