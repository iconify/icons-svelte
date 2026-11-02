<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqqss1byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqqss1byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ban-line" {...props}></Icon>
