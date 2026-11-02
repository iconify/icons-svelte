<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do5q-pbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do5q-pbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gesture-unlock-line" {...props}></Icon>
