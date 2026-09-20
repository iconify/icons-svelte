<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2wsx8prt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2wsx8prt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:map-filled" {...props}></Icon>
