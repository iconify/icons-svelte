<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnsfc7b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnsfc7b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:code-greater-than" {...props}></Icon>
