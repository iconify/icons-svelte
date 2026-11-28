<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ympbp5odk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ympbp5odk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-clock" {...props}></Icon>
