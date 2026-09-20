<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grgcn4rjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="grgcn4rjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:grid-alt" {...props}></Icon>
