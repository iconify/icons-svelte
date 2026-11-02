<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccjg7obml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccjg7obml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:earth-latitude-fill" {...props}></Icon>
