<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmrf4i1uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmrf4i1uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:path-intersect" {...props}></Icon>
