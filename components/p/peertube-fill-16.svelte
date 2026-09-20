<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbhtql8cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qbhtql8cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:peertube-fill-16" {...props}></Icon>
