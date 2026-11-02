<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn1dswbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn1dswbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pic-2-fill" {...props}></Icon>
