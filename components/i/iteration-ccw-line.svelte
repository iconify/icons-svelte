<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujz1ewbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujz1ewbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:iteration-ccw-line" {...props}></Icon>
