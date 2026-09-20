<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaih7sebo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aaih7sebo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-warning-line" {...props}></Icon>
