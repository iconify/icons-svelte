<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv_j_db-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv_j_db-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:door-closed" {...props}></Icon>
