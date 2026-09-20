<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz71kybyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="rz71kybyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:dice" {...props}></Icon>
