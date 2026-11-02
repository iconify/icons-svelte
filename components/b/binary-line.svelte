<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk2lv00-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk2lv00-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:binary-line" {...props}></Icon>
