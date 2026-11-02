<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr5g4pb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr5g4pb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:color-filter-fill" {...props}></Icon>
