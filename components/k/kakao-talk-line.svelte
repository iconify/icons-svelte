<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glq0v05nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glq0v05nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:kakao-talk-line" {...props}></Icon>
