<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hihb4h8dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hihb4h8dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:grid-3x3" {...props}></Icon>
