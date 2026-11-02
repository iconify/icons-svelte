<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt6z-vbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vt6z-vbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-automotive-fill" {...props}></Icon>
