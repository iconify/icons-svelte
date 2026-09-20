<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzdnue6lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzdnue6lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-fill" {...props}></Icon>
