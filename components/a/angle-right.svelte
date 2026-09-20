<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1c-5hbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1c-5hbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:angle-right" {...props}></Icon>
