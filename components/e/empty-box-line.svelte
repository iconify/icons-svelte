<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8i-qwj9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8i-qwj9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:empty-box-line" {...props}></Icon>
