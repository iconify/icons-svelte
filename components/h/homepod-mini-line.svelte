<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk-wzp8cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jk-wzp8cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:homepod-mini-line" {...props}></Icon>
