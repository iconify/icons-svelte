<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bos1cv4fn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bos1cv4fn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-x" {...props}></Icon>
