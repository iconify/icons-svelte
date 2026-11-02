<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvsj64bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvsj64bfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bluetooth-searching-line" {...props}></Icon>
