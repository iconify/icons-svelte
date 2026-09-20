<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj5q7orcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yj5q7orcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-cancel" {...props}></Icon>
