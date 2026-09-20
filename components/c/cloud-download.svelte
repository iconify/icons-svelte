<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb3yl8b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="zb3yl8b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:cloud-download" {...props}></Icon>
