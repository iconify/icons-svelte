<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw5tswbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw5tswbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:female-line" {...props}></Icon>
