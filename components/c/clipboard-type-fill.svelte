<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g48p0c9ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g48p0c9ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clipboard-type-fill" {...props}></Icon>
