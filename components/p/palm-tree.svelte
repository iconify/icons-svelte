<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziv56acgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziv56acgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:palm-tree" {...props}></Icon>
