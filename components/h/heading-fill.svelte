<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcy18ybbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcy18ybbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-fill" {...props}></Icon>
