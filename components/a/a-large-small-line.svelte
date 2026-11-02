<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbe-qwqtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbe-qwqtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:a-large-small-line" {...props}></Icon>
