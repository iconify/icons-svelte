<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7l4uhbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7l4uhbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:battery-3full-filled" {...props}></Icon>
