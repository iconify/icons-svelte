<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p65c6mbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p65c6mbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drive-line" {...props}></Icon>
