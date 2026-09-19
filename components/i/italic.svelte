<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfzwxubpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfzwxubpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:italic" {...props}></Icon>
