<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_iurvb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_iurvb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:component" {...props}></Icon>
