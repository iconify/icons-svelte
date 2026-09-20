<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxnkdnmvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxnkdnmvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-plus" {...props}></Icon>
