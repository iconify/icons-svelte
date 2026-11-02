<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm03p3z6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm03p3z6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-anticlockwise-1-fill" {...props}></Icon>
