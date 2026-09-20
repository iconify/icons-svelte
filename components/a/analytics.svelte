<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5o27lvyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5o27lvyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:analytics" {...props}></Icon>
