<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc_6ewbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wc_6ewbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:business-workflow-project-management" {...props}></Icon>
