<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpmordbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpmordbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-2-line" {...props}></Icon>
