<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvcclnx0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvcclnx0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paste-line" {...props}></Icon>
