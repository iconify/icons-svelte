<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb4c10b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="jb4c10b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:flip-vertical" {...props}></Icon>
