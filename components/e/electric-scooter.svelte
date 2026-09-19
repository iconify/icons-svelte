<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am-5-p8-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am-5-p8-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:electric-scooter" {...props}></Icon>
