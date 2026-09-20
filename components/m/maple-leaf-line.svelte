<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6fngdciu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6fngdciu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:maple-leaf-line" {...props}></Icon>
