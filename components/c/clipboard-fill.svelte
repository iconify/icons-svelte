<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-jp7lbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-jp7lbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clipboard-fill" {...props}></Icon>
