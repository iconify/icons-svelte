<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdhx6wxse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gdhx6wxse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:carplay-fill" {...props}></Icon>
