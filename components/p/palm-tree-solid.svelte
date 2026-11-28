<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2ndvpb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2ndvpb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:palm-tree-solid" {...props}></Icon>
