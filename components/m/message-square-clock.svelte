<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsfg5ubrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsfg5ubrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-square-clock" {...props}></Icon>
