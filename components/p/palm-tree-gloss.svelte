<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv9r2rbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv9r2rbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:palm-tree-gloss" {...props}></Icon>
