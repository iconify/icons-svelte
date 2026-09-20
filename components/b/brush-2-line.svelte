<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3kaibjqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3kaibjqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brush-2-line" {...props}></Icon>
