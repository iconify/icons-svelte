<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc4cq9s2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc4cq9s2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-audio-solid" {...props}></Icon>
