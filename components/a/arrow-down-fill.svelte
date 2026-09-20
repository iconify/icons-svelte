<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io4t3absr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io4t3absr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-down-fill" {...props}></Icon>
