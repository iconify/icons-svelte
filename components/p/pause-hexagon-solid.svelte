<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b624cwaib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b624cwaib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:pause-hexagon-solid" {...props}></Icon>
