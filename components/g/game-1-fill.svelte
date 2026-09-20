<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yja058bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yja058bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:game-1-fill" {...props}></Icon>
