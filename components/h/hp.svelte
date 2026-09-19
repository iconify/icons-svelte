<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lab98_byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lab98_byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:hp" {...props}></Icon>
