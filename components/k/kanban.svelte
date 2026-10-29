<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlephfb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlephfb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:kanban" {...props}></Icon>
