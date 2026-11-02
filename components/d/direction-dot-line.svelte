<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8ussty6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8ussty6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:direction-dot-line" {...props}></Icon>
