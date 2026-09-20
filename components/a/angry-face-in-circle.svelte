<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xma15acgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xma15acgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:angry-face-in-circle" {...props}></Icon>
