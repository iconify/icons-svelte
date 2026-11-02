<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r61kq0bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r61kq0bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-line" {...props}></Icon>
