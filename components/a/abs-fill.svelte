<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikvcxz5-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikvcxz5-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:abs-fill" {...props}></Icon>
