<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6w3d1k8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="d6w3d1k8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:query-pagination" {...props}></Icon>
