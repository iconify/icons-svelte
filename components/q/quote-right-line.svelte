<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe5zgaboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe5zgaboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:quote-right-line" {...props}></Icon>
