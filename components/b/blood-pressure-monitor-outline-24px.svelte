<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coygj3bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="coygj3bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-pressure-monitor-outline-24px" {...props}></Icon>
