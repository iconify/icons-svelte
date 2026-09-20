<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyw8m8bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyw8m8bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:package-2-line" {...props}></Icon>
