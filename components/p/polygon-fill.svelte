<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9q_8wb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9q_8wb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:polygon-fill" {...props}></Icon>
