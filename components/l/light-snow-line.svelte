<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odu7kactt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odu7kactt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:light-snow-line" {...props}></Icon>
