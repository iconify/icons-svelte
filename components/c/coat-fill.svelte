<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiasvibuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wiasvibuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:coat-fill" {...props}></Icon>
