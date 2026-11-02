<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwg7xg3gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwg7xg3gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:box-2-line" {...props}></Icon>
