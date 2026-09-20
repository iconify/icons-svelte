<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ritv8ybea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ritv8ybea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:monitor-warning-bold" {...props}></Icon>
