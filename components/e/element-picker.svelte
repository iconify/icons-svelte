<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5qe6qp3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x5qe6qp3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:element-picker" {...props}></Icon>
