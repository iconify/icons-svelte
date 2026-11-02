<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5w1ipogr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5w1ipogr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-root-line" {...props}></Icon>
