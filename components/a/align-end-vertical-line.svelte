<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lit144j4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lit144j4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-end-vertical-line" {...props}></Icon>
