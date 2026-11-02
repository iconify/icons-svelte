<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/air_i_kdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="air_i_kdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-terminal-fill" {...props}></Icon>
