<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnz4v1b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="nnz4v1b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:handle" {...props}></Icon>
