<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akud0m0pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akud0m0pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-check-fill" {...props}></Icon>
