<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm_7zbc9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jm_7zbc9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:house-plus-line" {...props}></Icon>
