<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd_096brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="jd_096brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:googleplus" {...props}></Icon>
