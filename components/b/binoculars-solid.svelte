<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juhzqac7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juhzqac7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:binoculars-solid" {...props}></Icon>
