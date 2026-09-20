<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4_nlmbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4_nlmbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airpods-line" {...props}></Icon>
