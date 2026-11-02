<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzgds-ntu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzgds-ntu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:indent-decrease-fill" {...props}></Icon>
