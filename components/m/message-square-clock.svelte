<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to89g0cag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to89g0cag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:message-square-clock" {...props}></Icon>
