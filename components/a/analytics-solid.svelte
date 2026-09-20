<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdn7ccb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdn7ccb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:analytics-solid" {...props}></Icon>
