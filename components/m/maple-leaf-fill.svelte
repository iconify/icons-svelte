<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aarmvfbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aarmvfbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:maple-leaf-fill" {...props}></Icon>
