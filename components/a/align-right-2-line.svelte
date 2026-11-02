<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srzp5ibqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srzp5ibqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-right-2-line" {...props}></Icon>
