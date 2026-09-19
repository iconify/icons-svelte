<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p517mpiuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1728,"height":1536};
const content = `<path class="p517mpiuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:flag" {...props}></Icon>
