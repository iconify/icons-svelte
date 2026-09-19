<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqrc5kb9t.css';
import '../../css/g/gldcflbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="lqrc5kb9t"/><path class="gldcflbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:folder-poi-o" {...props}></Icon>
