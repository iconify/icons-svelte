<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvh0v82tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvh0v82tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:message-square-question" {...props}></Icon>
