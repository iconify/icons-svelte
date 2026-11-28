<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw0l36hiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sw0l36hiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:message-square-alert" {...props}></Icon>
