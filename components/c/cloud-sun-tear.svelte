<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th7z8fm7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th7z8fm7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-sun-tear" {...props}></Icon>
