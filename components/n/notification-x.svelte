<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qag146y1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qag146y1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:notification-x" {...props}></Icon>
