<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8u1v1b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n8u1v1b5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:appleinc" {...props}></Icon>
