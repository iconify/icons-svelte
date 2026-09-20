<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_q6p6bet.css';
import '../../css/v/vo_do-qpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="d_q6p6bet"/><path class="vo_do-qpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:bluesky" {...props}></Icon>
