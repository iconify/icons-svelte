<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxaai3bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxaai3bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:code-xml" {...props}></Icon>
