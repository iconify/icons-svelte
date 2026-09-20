<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grw16xbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grw16xbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layers-line" {...props}></Icon>
