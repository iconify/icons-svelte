<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6j2iob0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="p6j2iob0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:post-comments-count" {...props}></Icon>
