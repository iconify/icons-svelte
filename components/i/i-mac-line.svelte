<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb3lsv9dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mb3lsv9dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:i-mac-line" {...props}></Icon>
