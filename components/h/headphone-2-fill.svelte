<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdwvkxblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jdwvkxblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:headphone-2-fill" {...props}></Icon>
