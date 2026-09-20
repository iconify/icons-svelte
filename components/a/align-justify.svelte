<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqk1152xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="tqk1152xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:align-justify" {...props}></Icon>
