<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl0qdpbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl0qdpbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:compass-4-line" {...props}></Icon>
