<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm4o4i1ir.css';
import '../../css/x/xh2cg4l2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm4o4i1ir"/><path class="xh2cg4l2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:article-solid" {...props}></Icon>
