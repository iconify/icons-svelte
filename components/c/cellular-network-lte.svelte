<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf6xnhbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zf6xnhbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:cellular-network-lte" {...props}></Icon>
