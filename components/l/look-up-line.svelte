<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-0vi6blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-0vi6blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:look-up-line" {...props}></Icon>
