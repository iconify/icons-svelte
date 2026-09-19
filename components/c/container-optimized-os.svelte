<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddgfu5xyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddgfu5xyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:container-optimized-os" {...props}></Icon>
