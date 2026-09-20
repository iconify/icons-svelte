<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm0iz-wcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm0iz-wcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-top-line" {...props}></Icon>
