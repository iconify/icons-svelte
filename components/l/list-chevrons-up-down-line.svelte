<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1y_ymb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1y_ymb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-chevrons-up-down-line" {...props}></Icon>
