<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvef6x8av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvef6x8av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:laptop-2-fill" {...props}></Icon>
