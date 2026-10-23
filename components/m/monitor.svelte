<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js_u-mblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js_u-mblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:monitor" {...props}></Icon>
