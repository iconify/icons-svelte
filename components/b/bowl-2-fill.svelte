<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pysi47ajq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pysi47ajq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bowl-2-fill" {...props}></Icon>
