<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls18477wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls18477wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-outer-fill" {...props}></Icon>
