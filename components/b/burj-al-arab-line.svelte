<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryydanbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryydanbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:burj-al-arab-line" {...props}></Icon>
