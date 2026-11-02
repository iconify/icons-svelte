<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tloiup0ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tloiup0ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:add-circle-line" {...props}></Icon>
