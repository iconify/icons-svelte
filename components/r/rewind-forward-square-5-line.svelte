<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyn8ona3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyn8ona3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-square-5-line" {...props}></Icon>
