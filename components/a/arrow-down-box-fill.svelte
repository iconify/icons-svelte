<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syavd4j4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="syavd4j4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-down-box-fill" {...props}></Icon>
