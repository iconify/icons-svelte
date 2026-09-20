<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyr66qbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyr66qbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-door-lock-open" {...props}></Icon>
